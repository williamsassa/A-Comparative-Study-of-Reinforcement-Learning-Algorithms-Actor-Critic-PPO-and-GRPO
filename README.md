 # A Comparative Study of Reinforcement Learning Algorithms: Actor-Critic, PPO, and GRPO
 
## Project Overview

**A comparative study of Reinforcement Learning algorithms: Actor-Critic, Proximal Policy Optimization (PPO), and Generalized Reinforcement Policy Optimization (GRPO).  
The project evaluates their performance, stability, and efficiency across CartPole, LunarLander, and language modeling tasks with DistilGPT2.**

Actor-Critic vs PPO vs GRPO – Benchmarks in RL & NLP

<p align="center">
<img src="comparaison/reward LunarLander.png" width="720"><br>
<i>Figure 1: Comparative RL Algorithms – Actor-Critic, PPO, GRPO</i>
</p>

## Highlights

- Three RL algorithms implemented: **Actor-Critic**, **PPO**, **GRPO**

- Benchmarks on **CartPole** and **LunarLander-v3** environments

- Application of PPO & GRPO to **Language Modeling** (DistilGPT2)

- Comparative analysis: convergence, robustness, efficiency

- Visualizations of **learning curves** and **performance metrics**

## Project Structure

Code
src/actor_critic/   → Actor-Critic implementation
src/ppo/            → PPO implementation (RL and LM)
src/grpo/           → GRPO implementation
src/common/         → Utilities and configuration
analysis/           → Scripts for results analysis
notebooks/          → Comparison and visualization notebooks
models/             → Trained models (CartPole, LunarLander, DistilGPT2)
references/         → Bibliography and related articles

## Technologies

- Python (PyTorch, NumPy, Matplotlib)

- Gymnasium / OpenAI Gym for RL environments

- Weights & Biases (wandb) for experiment tracking

- Jupyter Notebooks for analysis and visualization

## Quick Start

bash
# 1. Clone the repository
```bash
git clone https://github.com/williamsassa/A-Comparative-Study-of-Reinforcement-Learning-Algorithms-Actor-Critic-PPO-and-GRPO.git
cd A-Comparative-Study-of-Reinforcement-Learning-Algorithms-Actor-Critic-PPO-and-GRPO
```

# 2. Create and activate a virtual environment
```bash
python -m venv venv
```

```bash
source venv/bin/activate    # Linux / macOS
```

```bash
venv\Scripts\activate       # Windows
```

# 3. Install dependencies
```bash
pip install -r requirements.txt
```

# 4. Run experiments
```bash
python src/actor_critic/train.py   # Actor-Critic
python src/ppo/train.py            # PPO
python src/grpo/train.py           # GRPO
```

# 5. Analyze results

jupyter notebook notebooks/
Expected Results
Comparative benchmarks across multiple RL environments

Visualizations of learning curves and performance metrics

Insights into algorithm applicability in control tasks and NLP contexts
