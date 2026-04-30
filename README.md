# Federated Learning Experimental Analysis (IID vs Non-IID)

## 📌 Project Overview
This project implements a Federated Learning (FL) simulation system to analyze how data distribution affects model performance. The study compares three learning approaches:

- Centralized Learning
- Federated Learning with IID data
- Federated Learning with Non-IID data

The goal is to understand the trade-offs between privacy and performance in decentralized machine learning systems.

---

## 👨‍💻 Team Members
- Aniket (2210990114)
- Akshit Sharma (2210990094)
- Anmol Kaushik (2210990121)

---

## 🧠 Problem Statement
Traditional machine learning requires collecting data on a central server, which raises:

- Privacy concerns  
- Security risks  
- Regulatory issues  

Federated Learning solves this by keeping data on local devices and sharing only model updates.

---

## ⚙️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook / Google Colab  

---

## 📊 Methodology
The project follows a structured experimental approach:

### 1. Centralized Learning
- Model trained on full dataset  
- Used as baseline  

### 2. Federated Learning (IID)
- Data evenly distributed across clients  
- Local training + FedAvg aggregation  

### 3. Federated Learning (Non-IID)
- Data distributed unevenly  
- Each client has biased data  

---

## 🔁 Federated Training Process
- Global model sent to all clients  
- Each client trains locally  
- Model weights collected  
- Aggregation using FedAvg  
- Process repeated for multiple rounds  

---

## 📈 Results

| Model Type          | Accuracy |
|--------------------|---------|
| Centralized        | ~99.15% |
| Federated (IID)    | ~99.19% |
| Federated (Non-IID)| ~94.03% |

### 🔍 Key Observations
- IID ≈ Centralized performance  
- Non-IID reduces accuracy  
- Convergence slower in federated setup  
- Data distribution impacts model stability  

---

## 📊 Visualizations Included
- Accuracy vs Rounds  
- Loss vs Rounds  
- IID vs Non-IID Comparison  
- Client Data Distribution  
- Convergence Analysis  

---

## 🚀 Key Contribution
- Developed a configurable federated learning simulation system  
- Compared IID and Non-IID environments  
- Demonstrated impact of data heterogeneity on performance  
- Provided visualization-based analysis  

---

## ⚠️ Challenges Faced
- Handling Non-IID data distribution  
- Slower convergence in federated setup  
- Communication overhead  

---

## 🔮 Future Scope
- Implement advanced algorithms (FedProx, SCAFFOLD)  
- Use larger datasets (CIFAR-10, real-world data)  
- Increase number of clients  
- Add secure aggregation techniques  
- Deploy in real distributed environments  

---

## 📁 Project Structure
Project/
│
├── IPR Submission Proof/
├── Report and PPT/
├── Source Code/
│ └── federated_learning.ipynb
├── README.md

---

## 📌 Current Status
✔ Completed  
✔ Tested on IID and Non-IID scenarios  
✔ Results analyzed and documented  

---

## 📎 Notes
This project was developed as part of Industry Oriented Hands-On Experience (IOHE) at Chitkara University.

---