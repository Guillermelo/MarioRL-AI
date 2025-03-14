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
```
---

---

## 🚀 Running the Training

To start training the AI, run the `MarioAI.ipynb` notebook:

```bash
jupyter notebook MarioAI.ipynb
```

This will:
1. Set up the **Super Mario Bros** environment.
2. Apply **preprocessing steps** (grayscale, resizing, frame stacking).
3. Initialize and train the PPO model.
4. Save the trained model at regular intervals.

To visualize training progress using TensorBoard:

```bash
tensorboard --logdir ./logs/PPO_2
```

---

## 📊 Testing the Model

After training, you can test the model using `testit.ipynb`:

```bash
jupyter notebook testit.ipynb
```

This will:
- Load the trained PPO model.
- Run an episode in the Mario environment.
- Display real-time gameplay.

---

## 🔬 Current Progress

👉 **Implemented:**
- PPO-based training pipeline.
- Training loop with reward optimization.

🔄 **In Progress:**
- Hyperparameter tuning.
- Generalization across multiple levels.
- Advanced reward shaping.

🎯 **Next Steps:**
- Experiment with **different neural network architectures**.
- Implement **curriculum learning** for progressive difficulty.

---

## 📚 License

This project is for **educational and research purposes only**. All rights to *Super Mario Bros* belong to Nintendo. The AI model is trained in an **emulated environment** provided by **Gym-SuperMarioBros**.

---

Contributions and feedback are welcome! 🚀🎮

