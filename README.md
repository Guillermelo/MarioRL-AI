# 🎮 MarioRL-AI: Reinforcement Learning for Super Mario Bros

🚀 **MarioRL-AI** is a reinforcement learning project that trains an AI agent to play *Super Mario Bros* using **Proximal Policy Optimization (PPO)**. This project utilizes **Stable-Baselines3, Gym-SuperMarioBros, and OpenAI Gym** to develop a model capable of navigating through various levels while optimizing movement and decision-making.

## 📌 Features

- 🏆 **PPO-based reinforcement learning** for robust policy optimization.
- 🎮 **Integration with Gym-SuperMarioBros** for simulating the game environment.
- 🔍 **Custom reward system** to incentivize progress and efficient movement.
- 📊 **Performance logging** using TensorBoard for visual analysis.
- 🏗 **Frame processing** (grayscale conversion, resizing, and stacking) for improved model input.
- 🕹 **Custom action space** using `JoypadSpace` for simplified movement control.

---

## ⚙️ Installation

To set up the environment, install the required dependencies:

```bash
pip install stable-baselines3[extra] gymnasium shimmy torch torchvision torchaudio
pip install gym_super_mario_bros==7.3.0 nes_py tensorboard
