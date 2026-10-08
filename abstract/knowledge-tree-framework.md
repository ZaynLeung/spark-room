# AI 与机器人知识树框架

## 1. 研究总览：从根概念出发

- Artificial Intelligence (AI)
  - Machine Learning (ML)
  - Deep Learning (DL)
  - Reinforcement Learning (RL)
  - Computer Vision (CV)
  - Natural Language Processing (NLP)
  - Multimodal Learning
  - Embodied AI
  - Robotics
  - Control Theory

## 2. 深度学习（Deep Learning）

- Deep Learning
  - Neural Networks
    - MLP
    - CNN
    - RNN
    - Transformer
    - Diffusion Models
    - GNN
  - Optimization
    - SGD
    - Adam
    - Learning rate scheduling
    - Loss functions
  - Regularization
    - Dropout
    - Weight decay
    - BatchNorm
    - LayerNorm
  - Training Techniques
    - Pretraining
    - Fine-tuning
    - Distillation
    - LoRA
    - RLHF
  - Representation Learning
    - Feature extraction
    - Self-supervised learning
    - Contrastive learning

## 3. 强化学习（Reinforcement Learning）

- Reinforcement Learning
  - Fundamentals
    - Agent
    - Environment
    - State
    - Action
    - Reward
    - Policy
    - Value function
    - Bellman equation
  - Paradigms
    - Model-based RL
    - Model-free RL
    - Offline RL
    - Online RL
    - Multi-agent RL
    - Hierarchical RL
  - Algorithms
    - Value-based
      - Q-learning
      - DQN
      - Double DQN
      - Dueling DQN
    - Policy-based
      - REINFORCE
      - Actor-Critic
    - Modern Methods
      - PPO
      - TRPO
      - SAC
      - TD3
      - IMPALA
  - RL for Robotics
    - Sim-to-real
    - Sparse rewards
    - Exploration strategies
    - Goal-conditioned RL
    - Reward shaping

## 4. 控制理论（Control Theory）

- Control Theory
  - Classical Control
    - PID
    - Lead-lag compensator
    - Frequency response
  - Modern Control
    - State-space model
    - Observability
    - Controllability
    - LQR
    - LQG
    - Kalman filter
  - Robust Control
    - H-infinity
    - Model uncertainty
  - Optimal Control
    - MPC
    - Dynamic programming
    - Pontryagin principle
  - Adaptive Control
    - Parameter adaptation
    - System identification
  - Nonlinear Control
    - Feedback linearization
    - Lyapunov stability
    - Backstepping

## 5. 机器人学（Robotics）

- Robotics
  - Robot Kinematics
    - Forward kinematics
    - Inverse kinematics
    - Jacobian
  - Robot Dynamics
    - Newton-Euler
    - Lagrangian mechanics
    - Torque estimation
  - Perception
    - Vision
    - Depth sensing
    - LiDAR
    - Sensor fusion
  - Localization and Mapping
    - SLAM
    - Visual SLAM
    - Map representation
  - Planning
    - Path planning
    - Motion planning
    - Sampling-based methods
      - RRT
      - PRM
    - Search-based methods
      - A*
  - Manipulation
    - Grasping
    - In-hand manipulation
    - Task planning
  - Locomotion
    - Walking robots
    - Quadruped robots
    - Humanoid robots
  - Human-Robot Interaction
    - Shared autonomy
    - Teleoperation

## 6. VLM（Vision-Language Model）

- VLM
  - Core Idea
    - Joint visual-language understanding
    - Image-text alignment
  - Model Types
    - Contrastive models
      - CLIP
    - Generative models
      - BLIP
      - LLaVA
      - GPT-4o / vision-language models
  - Capabilities
    - Image captioning
    - Visual question answering
    - Grounded reasoning
    - OCR and document understanding
    - Open-vocabulary recognition
  - Training Methods
    - Pretraining on image-text pairs
    - Instruction tuning
    - Alignment tuning
  - Challenges
    - Hallucination
    - Long-context grounding
    - Spatial reasoning
    - Real-world bias

## 7. VLA（Vision-Language-Action）

- VLA
  - Motivation
    - Integrate perception, language, and action
    - Use foundation models as general decision-makers
  - Architecture
    - Vision encoder
    - Language encoder
    - Fusion module
    - Action head
    - Policy decoder
  - Action Representation
    - Discrete action tokens
    - Continuous control actions
    - Trajectory prediction
    - Keyframe action planning
  - Learning Paradigms
    - Behavior cloning
    - Diffusion policy
    - RL fine-tuning
    - Hybrid planning + control
  - Real Robot Challenges
    - Data scarcity
    - Generalization
    - Safety
    - Robotic embodiment gap
    - Sim-to-real transfer

## 8. Agent（智能体）

- Agent
  - LLM-based Agent
    - Planning
    - Tool use
    - Reflection
    - Memory
    - Self-improvement
  - Agent Types
    - Single-agent
    - Multi-agent
    - Hierarchical agent
    - Embodied agent
  - Core Modules
    - Perception
    - Reasoning
    - Planning
    - Action execution
    - Feedback loop
  - Challenges
    - Long-horizon planning
    - Tool misuse
    - Hallucination
    - Memory management
    - Safety and alignment

## 9. Embodied AI 与机器人智能体

- Embodied AI
  - Robot learning
  - Embodied perception
  - Language-conditioned control
  - Goal-conditioned behavior
  - Environment interaction loop
  - Active learning

- Robotics + Foundation Models
  - VLM for scene understanding
  - VLA for action generation
  - LLM for task planning
  - RL for policy optimization
  - World models for simulation and prediction

## 10. 多模态与世界模型（Multimodal / World Models）

- Multimodal Learning
  - Vision + Language
  - Vision + Action
  - Audio + Language
  - RGB + depth + tactile

- World Models
  - Forward model
  - Dynamics prediction
  - Model predictive control
  - Latent state representation
  - Counterfactual reasoning

## 11. 核心交叉关系

- Deep Learning
  - supports
    - VLM
    - RL
    - Agent
    - Robot perception

- Reinforcement Learning
  - supports
    - Robot control
    - Policy optimization
    - Agent decision-making

- Control Theory
  - supports
    - Robot dynamics
    - Stability analysis
    - Motion control

- VLM / VLA
  - connect
    - perception
    - language understanding
    - decision making
    - action execution

- Agent + Robotics
  - produce
    - Embodied intelligence
    - autonomous task execution
    - long-horizon manipulation

## 12. 建议的学习路径

- 第一层：Deep Learning + Control Theory + Robotics
- 第二层：Reinforcement Learning + VLM + Agent
- 第三层：VLA + Embodied AI + World Models
- 第四层：Multi-agent + Sim-to-real + Safe autonomous robots

## 13. 研究组织建议

- 按“基础理论 → 关键方法 → 具体应用 → 机器人实现”写资料
- 用根节点统一管理：AI / DL / RL / Control / Robotics / VLM / VLA / Agent
- 每个分支都要保留：
  - 基本定义
  - 关键方法
  - 代表论文/模型
  - 典型应用
  - 局限与挑战

## 14. 未来知识整理模板

- 主题：
- 根节点：
- 子分支：
- 关键方法：
- 代表工作：
- 应用场景：
- 挑战：
- 关系图：
- 结论：
