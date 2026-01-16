# Langgraph-Learning-Modules-CampusX

This repository documents my hands-on learning and experimentation with **LangGraph**, following the **CampusX LangGraph playlist**.
Each module demonstrates a core workflow pattern supported by LangGraph, implemented using Jupyter notebooks for clarity and step-by-step exploration.

---

## Repository Structure

```
Langgraph-Learning-Modules-CampusX
├── 1_sequential_flow
├── 2_parallel_flow
├── 3_conditional_flow
├── 4_iterative_flow
├── LICENSE
├── requirements.txt
└── README.md
```

---

## Workflow Modules

### 1. Sequential Flow

- **Concepts covered:**
  - Sequential node execution  
  - State passing across nodes  
  - Prompt chaining  

- **Notebooks:**
  - `1_bmi_calculator.ipynb` – Simple deterministic computation pipeline  
  - `2_simple_llm.ipynb` – Single-step LLM invocation  
  - `3_prompt_chaining.ipynb` – Multi-step prompt chaining using LangGraph  


### 2. Parallel Flow

- **Concepts covered:**
  - Parallel node execution  
  - Shared state aggregation  
  - Independent evaluation paths  

- **Notebooks:**
  - `1_batsman_workflow.ipynb` – Parallel analysis of a batsman’s performance  
  - `2_upsc_evaluator.ipynb` – Parallel evaluation of UPSC-style answers  

### 3. Conditional Flow

- **Concepts covered:**
  - Conditional edges  
  - Decision-based routing  
  - State-driven control flow  

- **Notebooks:**
  - `1_quadratic_solver.ipynb` – Route logic based on discriminant value  
  - `2_review_handling.ipynb` – Sentiment-based review handling workflow  


### 4. Iterative Flow

- **Concepts covered:**
  - Iterative execution  
  - Loop control using state  
  - Termination conditions  

- **Notebooks:**
  - `post_generator.ipynb` – Iterative content generation workflow

---

## Setup

### 1. Dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 2. Environment Variables:

Create a .env file in the project root and add:
```.env
GOOGLE_API_KEY=
```

Alternatively, you can rename `.env.example` to `.env` and update the value accordingly.

---

## License

This project is licensed under the MIT License.
