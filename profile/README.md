# Applied Reinforcement Learning — Student Agents Collection

Welcome to the GitHub organization that collects and curates **Reinforcement Learning agents developed by students** of the *Applied Reinforcement Learning* course at the **University of Genoa**.

This organization serves both as a showcase of student work and as a shared technical archive of implementations, experiments, and design choices emerging from the course’s project activities.

---

## Course Context

**Applied Reinforcement Learning**  
**Instructor:** [Prof. Riccardo Berta](https://about.me/riccardo.berta)

The course is offered within the Master’s Degree in [Electronic Engineering](https://corsi.unige.it/en/corsi/11970) at the [University of Genoa](https://unige.it/).  
Official course page: <https://corsi.unige.it/en/off.f/2025/ins/90595>

The focus of the course is the design and implementation of autonomous agents capable of perceiving, acting, and learning in unknown environments in order to achieve specific goals using reinforcement learning algorithms. Emphasis is placed on the full pipeline, from problem formulation to quantitative evaluation of agent performance.

---

## Purpose of This Organization

The repositories hosted here collect **student-developed reinforcement learning agents**, typically created as part of course projects, laboratories, or exam-related assignments. Each repository usually documents:

- the problem formulation in terms of states, actions, rewards, and policies;
- the reinforcement learning algorithms adopted, ranging from classical tabular approaches to deep reinforcement learning methods;
- the experimental setup, environments, and evaluation metrics;
- the implementation details, generally based on Python and Jupyter Notebooks.

The goal is to encourage good engineering practices, reproducibility, and critical comparison between different algorithmic choices, while also providing future students with concrete reference implementations.

---

## Learning Outcomes

Through the activities documented in these repositories, students demonstrate their ability to reason about autonomous agents using correct reinforcement learning terminology, to understand and critically analyze different classes of algorithms, and to quantitatively evaluate agent performance. The projects also reflect the capability to translate real-world problems into reinforcement learning formulations and to implement complete solutions using Python-based toolchains.

---

## Technical Stack

Most repositories rely on a common ecosystem centered on Python and Jupyter Notebooks. Widely used libraries and frameworks include Gymnasium for environments, TensorFlow or PyTorch for function approximation, and Matplotlib for visualization. Where relevant, optimized implementations from Stable Baselines, CleanRL, or similar libraries are employed or referenced.

Because GitHub’s native notebook viewer has limitations in rendering interactive plots and mathematical notation, notebooks are often best explored by running them locally or through external services such as Google Colab or nbviewer.

---

## Repository README Guidelines for Student Agents

Each repository in this organization must include a well-structured `README.md` file that clearly documents the developed reinforcement learning agent. The README is considered an integral part of the project and should allow a reader to understand *what problem is being solved, how it has been formulated as a reinforcement learning task, and how the proposed solution has been designed and evaluated*.

In particular, the README should address the following aspects.

### Problem Description and Environment

The README should begin with a clear description of the problem being tackled and the environment in which the agent operates. This includes the nature of the task, the objectives of the agent, and the characteristics of the environment, whether custom-designed or taken from an existing library such as Gymnasium. Any relevant assumptions or constraints should be made explicit.

### Reinforcement Learning Formulation

The problem must be formulated rigorously in reinforcement learning terms. The README should describe the state representation, the action space, and the reward function, explaining the rationale behind each design choice. If approximations or simplifications are introduced, these should be justified from both a theoretical and practical standpoint.

### Algorithmic Approach

The selected reinforcement learning algorithm or family of algorithms should be presented and motivated. The README should explain why the chosen approach is appropriate for the problem, referencing concepts discussed in the course such as value-based methods, policy-based methods, actor–critic architectures, or model-based techniques. Key hyperparameters and architectural choices should be described at a conceptual level.

### Implementation Details

A concise overview of the implementation should be provided, focusing on aspects that are essential to understanding or reproducing the work. This includes the software stack, the main libraries used, and the overall structure of the code. The README should indicate how training is performed and how the agent interacts with the environment during learning and evaluation.

### Experimental Setup and Evaluation

The README should describe how the agent’s performance is evaluated. This includes the metrics used, the training protocol, and any validation or testing procedures. Results should be summarized qualitatively and, where appropriate, quantitatively, with references to plots, tables, or logged data included in the repository.

### Results and Discussion

Beyond reporting results, the README should contain a brief discussion interpreting the observed behavior of the agent. This may include an analysis of convergence properties, stability issues, sample efficiency, or failure cases. Critical reflection on the limitations of the approach is encouraged.

### How to Run the Code

Clear instructions must be provided to allow others to reproduce the experiments. This includes environment setup, dependency installation, and the commands or notebooks required to train and evaluate the agent. If pre-trained models are provided, their usage should be explained.

### References

Any external resources used during the development of the project, such as papers, libraries, tutorials, or course materials, should be properly cited. This helps contextualize the work and acknowledges prior contributions.

---

## Recommended Background and Reading

The material collected here assumes familiarity with high-level programming in Python and a basic understanding of supervised machine learning. For deeper theoretical insight, the following texts are commonly referenced throughout the course:

- Miguel Morales, *Grokking Deep Reinforcement Learning*, Manning  
- Richard S. Sutton and Andrew G. Barto, *Reinforcement Learning: An Introduction*, MIT Press  

---

## Academic Use and Attribution

All repositories in this organization are intended for **educational and academic purposes**. Code and documentation are authored by students as part of their coursework. When reusing or extending any material, please respect the license specified in each repository and properly acknowledge the original authors.

---

## Disclaimer

The implementations hosted here are primarily learning artifacts. While they aim for clarity, correctness, and reproducibility, they are not guaranteed to be production-ready or optimized for industrial deployment.

---

If you are a student of the course, this organization represents both a contribution and a responsibility: document your work clearly, justify your design choices, and make your experiments understandable to others.
