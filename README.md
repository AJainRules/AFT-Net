🌾 AFT-Net: Privacy-Preserving Federated Learning with Blockchain for Smart Agriculture
📌 Overview

This repository implements AFT-Net (Adaptive Federated Transformer Network) — a novel federated learning framework designed for smart agriculture systems under real-world constraints such as:

Non-IID data distribution
Noisy sensor data
Missing data
Malicious participants
Privacy and trust requirements

The framework integrates:

🔒 Differential Privacy (DP)
🔗 Blockchain-based validation
📊 Attention-based deep learning model
⚖️ Reputation-Aware Federated Aggregation (RAFA)
🚀 Key Contributions
✅ Privacy-Preserving Federated Learning
✅ Blockchain-based Trust & Validation Layer
✅ Attention-Based Tabular Deep Learning Model
✅ Robustness to Non-IID, Noise, and Missing Data
✅ Reputation-Aware Aggregation (RAFA)
✅ Communication-Efficient Sparse Updates
🧠 Architecture Overview

The AFT-Net pipeline consists of:

Data Collection (IoT/IoMT Sensors)
Preprocessing (Imputation + Scaling)
Client-Side Training
Differential Privacy Injection
Sparse Model Updates
Blockchain Validation
Reputation-Based Aggregation
Global Model Update
📂 Project Structure
.
├── main.py / notebook
├── aft_net_research_outputs/
│   ├── main_model_comparison.csv
│   ├── system_level_comparison.csv
│   ├── robustness_stress_tests.csv
│   ├── fedavg_history.csv
│   ├── aft_net_history.csv
│   ├── blockchain_audit_ledger.csv
│   ├── ledger_hash_chain.json
│   ├── plots/
│   │   ├── predictive_performance.png
│   │   ├── convergence.png
│   │   ├── privacy_score.png
│   │   └── ...
└── README.md
⚙️ Installation
1. Clone Repository
git clone https://github.com/your-username/aft-net.git
cd aft-net
2. Install Dependencies
pip install -r requirements.txt
Required Libraries
numpy
pandas
matplotlib
seaborn
scikit-learn
torch
xgboost (optional)
▶️ How to Run
python main.py

OR run the notebook step-by-step.

📊 Experiments Included
1. Centralized Baselines
Random Forest
SVM
XGBoost (if installed)
2. Federated Models
FedAvg
AFT-Net (Proposed)
📈 Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
Privacy Score
Communication Cost
Trust & Security Score
🔬 Stress Testing

The model is evaluated under:

Scenario	Description
Non-IID	Dirichlet distribution (α variation)
Noise	Gaussian noise injection
Missing Data	Random missing values
Malicious Clients	Label shuffling + weight perturbation
🔗 Blockchain Validation

A simulated blockchain layer ensures:

✔️ Update authenticity (hash-based validation)
✔️ Malicious client detection
✔️ Reputation tracking
✔️ Immutable audit logs

Output files:

blockchain_audit_ledger.csv
ledger_hash_chain.json
🧮 Key Results
Model	Accuracy	Privacy	Trust
FedAvg	Low	Medium	❌
AFT-Net	High	High	✅

👉 AFT-Net significantly outperforms FedAvg in:

Non-IID environments
Noisy data
Missing data scenarios
📊 Visualization Outputs

The code generates:

📉 Convergence plots
📊 Performance comparison
🔒 Privacy score analysis
📡 Communication efficiency
🛡️ Blockchain validation stats
🧠 Feature attention importance
🧪 Dataset
Uses Crop Recommendation Dataset (if available)
Otherwise generates synthetic agricultural dataset

Features:

N, P, K, temperature, humidity, pH, rainfall

Target:

Crop label
🔐 Privacy Mechanisms
Differential Privacy Noise Injection
Partial Data Sharing
Sparse Model Updates
📡 Communication Optimization
Sparse gradient sharing
Reduced bandwidth usage
Communication cost tracking (MB)

👨‍💻 Author
Apoorv Jain
Assistant Professor | Data Analyst | Blockchain Researcher
IIT Patna (M.Tech - Big Data & Blockchain)

⭐ Citation

If you use this work, please cite:

@article{aftnet2026,
  title={AFT-Net: Privacy-Preserving Federated Learning with Blockchain for Smart Agriculture},
  author={Apoorv Jain},
  year={2026}
}
🤝 Contributing

Contributions are welcome!
Feel free to open issues or submit pull requests.

📬 Contact

For queries or collaborations:
📧 apoorv.jain@niet.co.in
