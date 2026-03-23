# 🧠 Software Quality Analysis using inFusion

![Tool](https://img.shields.io/badge/Tool-inFusion-blue)
![Language](https://img.shields.io/badge/Language-Java-orange)
![Analysis](https://img.shields.io/badge/Type-Static%20Analysis-green)
![Focus](https://img.shields.io/badge/Focus-Design%20Flaws-red)

---

## 📌 Overview

This project presents a **longitudinal software quality analysis** of the open-source Java library **Apache Commons Lang**, focusing on the detection and evolution of **design flaws (anti-patterns)** across multiple versions.

Using the commercial static analysis tool **inFusion**, this study evaluates how core software quality attributes evolve as the system matures.

---

## 🎯 Objectives

- Detect and analyze **software anti-patterns** (code smells)
- Measure **quality deficit indices** across versions
- Understand how **software design quality evolves over time**
- Identify **critical architectural weaknesses**

---

## 🛠️ Tools & Technologies

- **inFusion** → Design flaw detection & quality metrics  
- **Microsoft Excel** → Data processing & visualization  
- **Java (Apache Commons Lang)** → Subject system  

---

## 📂 Project Analyzed

**Apache Commons Lang**

- Open-source Java utility library
- Medium-sized system (< 100,000 LOC)
- Widely used in real-world applications

🔗 Repository: https://github.com/apache/commons-lang

---

## 📊 Versions Analyzed

| Version |
|--------|
| 3.16 |
| 3.17 |
| 3.18 |
| 3.19 |
| 3.20 |

---

## 📈 Metrics Collected

The following **quality dimensions** were analyzed:

- **Complexity**
- **Coupling**
- **Cohesion**
- **Encapsulation**
- **Inheritance**
- **Overall Quality Deficit Index**

Each metric represents the severity of design flaws affecting that dimension.

---
## 📊 Types of Analysis

This project includes **two levels of analysis**:

---

### 1️⃣ Raw Design Flaw Counts

These represent the **absolute number of detected issues** in each version:

- Complexity flaws  
- Coupling flaws  
- Cohesion flaws  
- Encapsulation flaws  
- Inheritance flaws  
- Total design flaws  

📌 These help answer:  
**“How many issues exist in the system?”**

---

### 2️⃣ Quality Deficit Indices

These represent the **severity and impact of design flaws**, normalized by system characteristics:

- Complexity deficit  
- Coupling deficit  
- Cohesion deficit  
- Encapsulation deficit  
- Inheritance deficit  
- Overall Quality Deficit Index  

📌 These help answer:  
**“How severe are the design issues?”**

---

### 🔍 Why Both Matter

- Raw counts show the **volume of issues**
- Deficit indices show the **architectural impact of those issues**

Together, they provide a **more complete and meaningful understanding of software quality evolution**

---

## 🔍 Key Findings

### 🚨 Highest Design Deficits
- **Coupling** and **Complexity** consistently showed the highest deficits  
- Indicates strong interdependencies and structural complexity issues  

### 📉 Quality Improvement Over Time
- Significant reduction in:
  - Coupling deficit (3.6 → 2.7)
  - Complexity deficit (3.4 → 2.9)
- Suggests **refactoring and architectural improvements**

### ⚖️ Stable Metrics
- Cohesion remained constant across all versions  
- Encapsulation showed minimal variation  

### 📊 Overall Trend
- Quality Deficit Index improved:
1.8 → 1.8 → 1.5 → 1.4 → 1.5

- Indicates **controlled evolution with minor regression in later version**

---

## 📁 Repository Structure
├── Report.pdf # Full analysis report  
├── CommonsLang_Detection.xlsx # Raw data + graphs  
├── graphs/ # Exported visualizations  
&nbsp;|&emsp;&emsp;&emsp;├── raw_counts/  
&nbsp;|&emsp;&emsp;&emsp;└── deficit_indices/  
├── infusion_screenshots/ # Tool outputs   
└── README.md  


---

## 🧪 Methodology

1. Selected a real-world Java project with multiple versions  
2. Analyzed each version using **inFusion**  
3. Extracted:
   - Design flaw counts
   - Quality deficit indices  
4. Exported results to Excel  
5. Generated graphs to visualize trends  
6. Interpreted evolution of software quality  

---

## ⚠️ Disclaimer

This repository **does NOT contain the source code** of Apache Commons Lang.

All analysis was conducted on publicly available open-source software:

🔗 https://github.com/apache/commons-lang

This repository only contains:
- Analytical results  
- Visualizations  
- Interpretations  

---

## 💡 Key Takeaway

Even as software systems evolve, **design quality does not have to degrade**.

This analysis demonstrates that:
- Continuous monitoring
- Refactoring efforts  
- Tool-assisted analysis  

can lead to **improved architectural quality over time**

---

## If You Found This Interesting

Feel free to ⭐ the repo or connect with me!
