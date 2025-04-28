# Codon Bias and Process Optimization in Prokaryotes

![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg)

---

## 📚 Overview

Codon usage bias plays a vital role in gene expression levels in prokaryotes like *Escherichia coli*.  
This project focuses on optimizing gene sequences for better protein expression by analyzing and adjusting codon usage patterns based on key metrics like:

- **Relative Synonymous Codon Usage (RSCU)**
- **Codon Adaptation Index (CAI)**
- **GC Content**

The optimization is performed using **Dynamic Programming (DP)** and **Genetic Algorithm (GA)** techniques.

---

## ❓ Problem Statement

Despite advances in synthetic biology, foreign genes often express poorly in prokaryotes due to mismatched codon usage.  
This project addresses the challenge of optimizing gene sequences computationally to align with host codon preferences, enhancing translational efficiency and stability.

---

## 🎯 Objectives
- Analyze codon usage bias in *E. coli* genome.
- Implement Dynamic Programming (DP) for codon selection.
- Apply Genetic Algorithm (GA) for evolutionary optimization.
- Compare optimization results on CAI, RSCU balance, and GC content.
- Provide a computational framework for future codon optimization tasks.

---

## 🛠️ Technologies Used
- **Python 3.8+**
- **BioPython** — for sequence processing.
- **NumPy** — for numerical operations.
- **SciPy** — for optimization routines.
- **Matplotlib** — for visualization.

---

## 📂 Project Structure
```plaintext
├── code.py        # Main script for codon optimization
├── README.md      # Project documentation
```

---

## 📂 Files
| File         | Description |
|--------------|-------------|
| `code.py`    | Main code to perform codon bias analysis, DP optimization, and GA optimization. |

---

## 🚀 How to Run
1. **Clone the repository:**
```bash
git clone https://github.com/your_username/your_repo_name.git
cd your_repo_name
```

2. **Install required packages:**
```bash
pip install -r requirements.txt
```

3. **Run the main script:**
```bash
python code.py
```

---

## 🧪 Methodology

- **Dataset:**  
  E. coli strain MB30 complete genome (NCBI GenBank).

- **Codon Analysis:**  
  Calculate RSCU values, CAI scores, and GC content from coding sequences.

- **Optimization Techniques:**  
  - **Dynamic Programming (DP):** Selects best codon sequence using scoring matrices.
  - **Genetic Algorithm (GA):** Evolves codon sequences using crossover and mutation.

- **Evaluation:**  
  Improvements are measured by:
  - CAI Score
  - GC Content Balance
  - RSCU Uniformity

---

## 📈 Results

The optimization results show:

- Significant increase in **CAI scores** (translational efficiency).
- Balanced **GC content** matching native E. coli levels.
- Reduced codon usage bias improving mRNA stability.


---

## 🔥 Future Scope
- Integrate tRNA abundance metrics for even better optimization.
- Expand optimization to multi-species codon bias (cross-host expression).
- Validate results with **wet-lab experimental testing**.
- Extend GA models with advanced crossover and fitness functions.

---


---

---

# 🧬 Thank you for exploring Codon Bias Optimization!
⭐ Star this repo if you find it useful!
