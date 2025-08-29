# Toward-Precision-Oncology-Reinforcement-Guided-GPT-Pipeline-for-EGFR-Inhibitor-Discovery
Generating new drug-like molecules is a complex
and time-intensive process, often requiring the evaluation of
thousands of compounds. Traditional trial-and-error methods
are costly and uncertain, highlighting the need for smarter
generative approaches. Recent studies have explored deep learn-
ing and reinforcement learning (RL) for molecular generation,
with models like ReLeaSE, REINVENT, and ChemGPT showing
promise. However, few approaches have directly applied RL
with pretrained chemical language models to generate EGFR-
specific inhibitors. We propose a reinforcement learning (RL)-
based framework for EGFR-specific drug design, integrating
a Transformer-based chemical language model (cMolGPT), a
property predictor (XGBoost), and Proximal Policy Optimization
(PPO). Using the ChEMBL203 dataset, the model was guided
to generate molecules with high predicted pIC50 values through
a custom reward function. Experimental results show that the
XGBoost model achieved strong predictive performance (R2 =
0.7475, MAE = 0.5111), making it effective in guiding the RL pro-
cess. The generated molecules displayed high predicted activity,
favorable lipophilicity, and a diverse range of molecular weights,
which indicates strong drug-likeness and target specificity.These
results confirm the effectiveness of our framework in generating
valid, potent, and target-specific molecules
