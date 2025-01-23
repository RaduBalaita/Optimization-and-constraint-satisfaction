# Optimization & Constraint Satisfaction Labs

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](OCS.ipynb)
[![Python 3.12](https://img.shields.io/badge/Python-3.12-blue)](https://www.python.org/)

**Repository showcasing 6 labs from the *Optimization and Constraint Satisfaction* course**, implementing metaheuristic algorithms for solving shifted/rotated benchmark functions. Designed to demonstrate hands-on experience with evolutionary computation and numerical optimization.

---

## 🧪 Labs Overview

### **Lab 1: Benchmark Function Design**  
**Objective**: Implement 5 CEC-inspired optimization functions with shifting/rotation.  
- Built a modular `Function` class to handle bounds, shifting (`o` vector), and bias.  
- Functions: Shifted Sphere, Schwefel 1.2, Rotated Elliptic, Noisy Schwefel, Schwefel 2.6.  
- **Key Skill**: Problem formulation for optimization landscapes.  

### **Lab 2: Self-Adaptive Random Search**  
**Objective**: Develop a population-based optimizer with dynamic step size.  
- Implemented `PopulationV3_SelfAdaptive` with fitness-driven alpha adjustment.  
- Features: Multi-agent generation, variable population, bounds enforcement.  
- **Key Skill**: Balancing exploration/exploitation in stochastic search.  

### **Lab 3: Canonical Genetic Algorithm (CGA)**  
**Objective**: Binary-encoded GA with greedy replacement.  
- Designed 64-bit binary encoding/decoding utilities.  
- Features: Roulette selection, single-point crossover, bit-flip mutation.  
- **Key Skill**: Evolutionary algorithm design for discrete optimization.  

### **Lab 4: Real-Coded Genetic Algorithm (RGA)**  
**Objective**: Continuous-space GA with adaptive parameters.  
- Implemented BLX-0.1 crossover and Gaussian mutation.  
- Features: Fitness-based `pc`/`pm` adaptation.  
- **Key Skill**: Real-valued optimization and parameter tuning.  

### **Lab 5: Differential Evolution (DE/best/2/exp)**  
**Objective**: Advanced DE variant for numerical optimization.  
- Built mutation using best solution + two differential terms.  
- Features: Exponential crossover, fixed `F=0.8`, `CR=0.9`.  
- **Key Skill**: Leveraging differentiation for global optimization.  

### **Lab 6: Metaheuristic Benchmarking**  
**Objective**: Compare algorithms on Sphere/Rastrigin/Rosenbrock (5D/10D).  
- GPU-accelerated fitness evaluation with `CuPy`.  
- Analyzed convergence plots and statistical metrics (mean, std, min/max).  
- **Key Skill**: Performance analysis and GPU-accelerated computing.  

---

## 🛠️ Tools & Technologies  
- **Core**: Python, NumPy, Jupyter  
- **Optimization**: Custom implementations of GA, DE, Random Search variants  
- **Acceleration**: CuPy for GPU parallelism  
- **Analysis**: Matplotlib, Pandas  

---

## 📚 Key Learnings  
1. **Algorithm Design**: Built evolutionary algorithms from scratch (GA/DE).  
2. **Problem Formulation**: Engineered benchmark functions mimicking real-world optimization challenges.  
3. **High-Dimensional Optimization**: Tested algorithms on 5D/10D problems with rotation/shifting.  
4. **Performance Analysis**: Compared convergence speed, robustness, and scalability.  
5. **Adaptive Strategies**: Implemented self-tuning parameters for mutation/crossover.  
