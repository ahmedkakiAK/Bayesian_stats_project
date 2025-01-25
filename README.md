# Bayesian Statistical Analysis: Exploring Diabetes and Energy Consumption Data  

## Overview  
This project applies Bayesian methods to analyze two datasets: the **National Institute of Diabetes and Digestive and Kidney Diseases’ (NIDDK) diabetes dataset** and the **PJM Interconnection’s hourly energy consumption dataset**. Inspired by the 2017 paper *"Deep Learning: A Bayesian Perspective"*, we implement Bayesian approaches to showcase their strengths, challenges, and the potential for broader applications in statistical analysis. We also explore advancements in Bayesian methodologies since the paper’s publication.  

## Authors  
- 🔹 **[Zakarya Elmimouni]** – [ENSAE] 
- 🔹 **[Ahmed Khairaldin]** – [ENSAE] 
- 🔹 **[Amine Razig]** – [ENSAE] 

## Table of Contents  
1. [Objective](#objective)  
2. [Datasets](#datasets)  
3. [Techniques and Methods](#techniques-and-methods)  
4. [Simulation Study](#simulation-study)  
5. [How to Run the Project](#how-to-run-the-project)  
6. [Requirements](#requirements)  

## Objective  
The primary objective of this project is to demonstrate the advantages and challenges of Bayesian methods when applied to real-world data. We aim to:  
1. Explore Bayesian methods for analyzing the diabetes and energy consumption datasets.  
2. Develop a simulation study to evaluate the methods' robustness and effectiveness.  
3. Discuss advancements in Bayesian techniques since the publication of the foundational paper.  

## 📊 Datasets  

1. **National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK) Diabetes Dataset**  
   - **Description**: Medical data on factors influencing diabetes progression, including age, BMI, blood pressure, and glucose levels.  
   - **Purpose**: Analyze how Bayesian methods can provide insights into the relationships between predictors and the likelihood of diabetes.  

2. **PJM Interconnection Hourly Energy Consumption Dataset**  
   - **Description**: Time series data capturing hourly energy consumption for regional transmission operators.  
   - **Purpose**: Explore Bayesian approaches for modeling and predicting energy usage patterns over time.  

## Techniques and Methods  in the report : 

1. **MLP**  
2. **Markov Chain Monte Carlo (MCMC)**  
   - sampling and estimating posterior distributions.
3. **Bayesian Neural Networks**  
   - Inspired by the original paper, implemented for exploring complex relationships in the data.  


## How to Run the Project  

### Step 1: Clone the Repository  
```bash  
git clone https://github.com/[your-repo]/Bayesian-Analysis-Project.git 
cd Bayesian-Analysis-Project  
```  

### Step 2: Install Dependencies  
Ensure **Python 3.8+** is installed, then run:  
```bash  
pip install -r requirements.txt  
```  

### Step 3: Explore the Data and Methods  

#### Model Implementation  
- Bayesian models are implemented in separate files

Run these notebooks individually to explore specific methods.  

### Step 4: Results and Visualizations  
- Key results, including posterior distributions and predictive performance, are visualized in each method-specific notebook.  

## Requirements  
- **Python 3.8+**  
- Libraries:  
  - `numpy`  
  - `pandas`  
  - `matplotlib`  
  - `seaborn`  
  - `scipy`  
  - `pymc3`  
  - `tensorflow` (for Bayesian Neural Networks)  
- **Optional**: GPU for accelerated computation with neural models.  

---  

This README balances technical detail and clarity, ensuring reproducibility for anyone interested in the project.
