# 🧬 GeneCompare3X – Triple-Method DNA Similarity Analyzer

### 🔹 A GUI-based Python tool for comparing DNA sequences using Hamming, Jaro–Winkler, and Smith–Waterman algorithms.

---

## 🚀 Overview
**GeneCompare3X** is a Python-based DNA sequence similarity analyzer that compares two DNA sequences using three algorithms — **Hamming Distance**, **Jaro–Winkler Similarity**, and **Smith–Waterman Local Alignment**.  
It provides an **interactive Tkinter GUI** that supports **manual input** or **CSV/Excel-based input**, and displays similarity scores in real-time.

---

## ⚙️ Features
- Tkinter-based GUI  
- Manual or CSV/Excel input  
- Implements three algorithms  
- “Compare All” option for full analysis  
- Displays percentage similarity instantly  

---

## 🧩 Algorithms Implemented

| Algorithm | Handles Gaps | Speed | Accuracy | Ideal For |
|------------|---------------|--------|-----------|------------|
| **Hamming** | ❌ | 🚀 Fast | Basic | Equal-length, simple sequences |
| **Jaro–Winkler** | ❌ | ⚡ Moderate | Moderate | Slightly rearranged or short sequences |
| **Smith–Waterman** | ✅ | 🐢 Slow | ✅ Highest | Biologically meaningful comparison |

---

## 🧰 Tech Stack
- **Python 3.x**  
- **Tkinter** (GUI)  
- **Pandas** (CSV/Excel handling)  
- **Jupyter Notebook / VS Code**

---

## 🖥️ GUI Overview
The interface allows:
- DNA sequence input (manual or file-based)
- Algorithm selection: Hamming, Jaro–Winkler, Smith–Waterman, or Compare All
- Displays similarity results in real-time

