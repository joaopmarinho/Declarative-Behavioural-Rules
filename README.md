# Declarative Behavioural Rules with Declare

This project demonstrates the use of **declarative process modeling** using the **Declare** framework in Python. It focuses on defining and analyzing business process constraints through a flexible, rule-based approach.

## 🧩 Project Overview

The repository provides an example of how to model and evaluate business processes through **behavioral rules**. Unlike traditional imperative models, Declare allows the specification of process constraints without prescribing exact execution paths. This flexibility is ideal for scenarios where processes are loosely structured or evolve frequently.

### Main Goals

- Explore **declarative process modeling** using the Declare framework
- Apply constraints to event logs for process analysis
- Test and validate business logic against real or synthetic data

---

## 📂 Structure

📁 Declarative-Behavioural-Rules
├── declare.ipynb # Main notebook implementing declarative rules
├── unidade_teste_1.csv # Sample dataset representing a process log
└── README.md # Project documentation


### Key Components

- **`declare.ipynb`**: Contains Python code and explanations for defining Declare constraints, importing and analyzing event logs, and interpreting results.
- **`unidade_teste_1.csv`**: A sample CSV file representing an event log, used for testing the behavioral constraints.
- **Declare Constraints**:
  - `Response(A, B)`: If activity A occurs, B must eventually follow
  - `Precedence(B, A)`: B can only occur if A has occurred before
  - `Not Co-Existence(A, B)`: A and B cannot both appear in the same case
  *(and others)*
  - Any other constraints can be checked on the references, page 111.

---

## 🔧 Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- Custom implementation of Declare constraints

---

## 📈 Skills Demonstrated

- Process mining fundamentals
- Declarative modeling (Declare)
- Data manipulation and validation using event logs
- Rule-based logic implementation
- Use of Jupyter for reproducible data science workflows

---

## 📌 Use Case

This type of modeling is useful in:

- Compliance checking
- Audit and legal process validation
- Discovering hidden process constraints from log data
- Business process flexibility modeling

---

## 🚀 Getting Started[](url)

To run the notebook:

1. Clone the repository:
   ```bash
   git clone https://github.com/joaopmarinho/Declarative-Behavioural-Rules
   cd Declarative-Behavioural-Rules
2. Install the required Python packages (typically pandas and jupyter)

3. Run declare.ipynb in Jupyter Notebook or Jupyter Lab

 📫 About
This repository was created as a practical exploration of declarative process logic. It is ideal for showcasing skills in process mining, business rules modeling, and logic validation with real-world applications in BPM (Business Process Management).


---

Let me know if you’d like to tailor it for a specific company or role (e.g., data analyst, BPM consultant, compliance tech), or add a personal note at the end like "Developed as part of a process mining portfolio."

📚 References
- VAN DER AALST, Wil M. P.; CARMONA, Josep (Ed.). *Process Mining Handbook*. Cham: Springer, 2022. (Lecture Notes in Business Information Processing, v. 448). Disponível em: https://doi.org/10.1007/978-3-031-08848-3. Acesso em: 30 maio 2025.

