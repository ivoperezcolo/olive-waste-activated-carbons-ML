# 🌱 Machine Learning Prediction of Specific Capacitance in Activated Carbons from Olive Waste

Welcome! 👋  
This repository contains the **experimental dataset** used to predict the *specific capacitance (Cs)* of **activated carbons derived from olive mill waste** using machine learning methods.

The data were obtained from laboratory-scale syntheses of activated carbons through **chemical activation with KOH**, followed by **textural and electrochemical characterization**. These data support the research on **valorization of agro-industrial waste** for energy storage applications ⚡.

---

## 📘 Dataset Description

The dataset contains **experimental and derived variables** describing the synthesis conditions, physicochemical properties, and electrochemical performance of the activated carbons.


| Variable | Abbreviation | Unit | Description |
|-----------|---------------|------|-------------|
| Impregnation Ratio | **IR** | g/g | Ratio of KOH to precursor during chemical activation |
| Activation Temperature | **Tact** | °C | Temperature at which activation was performed |
| Activation Time | **tact** | min | Duration of the activation step |
| Specific Surface Area | **SBET** | m²/g | Surface area obtained by BET method |
| Total Pore Volume | **Vtotal** | cm³/g | Total pore volume at relative pressure P/P₀ ≈ 0.98 |
| Microporous Volume | **Vmicro** | cm³/g | Micropore volume determined by Dubinin–Radushkevich method |
| Average Pore Density | **Davg** | nm | Average pore density |
| Average Pore Size and Distribution | **PSDavg** | nm | Mean pore size and distribution width |
| Current Density | **j** | A/g | Applied current density during electrochemical test |
| Specific Capacitance | **Cs** | F/g | Gravimetric capacitance obtained from GCD measurements |

---

## 🧠 Usage

You can load the dataset easily using Python:

```python
import pandas as pd

df = pd.read_csv('data/activated_carbons.csv')
print(df.head())
