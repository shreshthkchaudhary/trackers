# AI/ML Research Runway — Master Prep Tracker

A standalone, dark-themed, zero-friction web application designed for students balancing **B.Tech Semester III (K.R. Mangalam University)** with long-term **AI/ML Research Scientist Aspirations** (targeting premier research internships at IITs, IISc, Google DeepMind, MSR, and FAIR for Summer 2027).

---

## 🚀 Quick Start

1. Open `index.html` directly in any modern web browser (Chrome, Edge, Brave, Firefox, Safari):
   - Full path: `C:\Users\ishu9\Downloads\CODE\track\aiml-tracker\index.html`
   - *Zero build step, zero `npm install`, zero server requirement. 100% offline-ready.*
2. Bookmark the page in your browser toolbar (`Ctrl + D`) for your daily **7:05 PM – 8:05 PM** evening study slot and Saturday morning deep block.

---

## 🎯 Academic & Strategic Profile

| Parameter | Current Status & Target | Strategic Implication |
| :--- | :--- | :--- |
| **Academic Standing** | B.Tech CSE (Semester III) | Enrolled in core CS & CCST courses at KRMU. |
| **Cumulative GPA** | **9.2 CGPA** *(Must Defend)* | Top tier of batch; essential credential for professor outreach and research fellowships. |
| **Summer Milestone** | **Cisco CCST Cybersecurity (982/1000)** | Summer internship formality 100% completed. Zero backlog or stress. |
| **Restart Date** | **September 09 / 10, 2026** | Timetable and phases re-anchored around actual university exam dates. |
| **Target Destination** | **Summer 2027 Research Internship** | Top AI labs (IIT Bombay, IIT Delhi, IISc CSA/CDS, DeepMind, MSR). |

---

## 🧠 The 7-Phase Curriculum Roadmap

The roadmap is structured sequentially to prevent the fatal mistake of stacking too many complex tracks simultaneously, weaving in Calculus, front-loading Probability before PyTorch, distributing writing checkpoints throughout, and culminating in the Summer 2027 Research Runway:

```
[Phase 1: Python OOP] ──> [Phase 2: Project + LA Intro] ──> [Phase 3: LA + NumPy Paired]
                                                                        │
                                  ┌─────────────────────────────────────┘
                                  ▼
                     [🛑 Mid-Term Exam Blackout]
                                  │
                                  ▼
[Phase 4: Calculus + Andrew Ng Course 1] ──> [Phase 5: Backprop Calculus + Course 2] ──> [🛑 End-Term Blackout]
                                                                                              │
                                  ┌───────────────────────────────────────────────────────────┘
                                  ▼
                     [Phase 6: Probability + Winter PyTorch Sprint]
                                  │
                                  ▼
                     [Phase 7: Even Semester & Summer Research Runway]
```

### Phase 1: Python OOP & Code Hygiene (Sep 09 – Sep 15)
*Master classes, inheritance, dunder methods, and decorators so you never write messy procedural scripts again.*
- **Video 1**: [Classes and Instances (ZDa-Z5JzLYM)](https://www.youtube.com/watch?v=ZDa-Z5JzLYM) — `self`, `__init__`, instance attributes.
- **Video 2**: [Class Variables (BJ-VvGyQxho)](https://www.youtube.com/watch?v=BJ-VvGyQxho) — Class namespace vs instance namespace.
- **Video 3**: [Classmethods and Staticmethods (rq8cL2XMM5M)](https://www.youtube.com/watch?v=rq8cL2XMM5M) — Alternate constructors via `@classmethod`.
- **Video 4**: [Inheritance & Subclasses (RSl87lqOXDE)](https://www.youtube.com/watch?v=RSl87lqOXDE) — `super().__init__()`, `isinstance()`, `issubclass()`.
- **Video 5**: [Special (Dunder) Methods (3ohzBxoFHAY)](https://www.youtube.com/watch?v=3ohzBxoFHAY) — `__repr__`, `__str__`, `__add__`, `__len__`.
- **Video 6**: [Property Decorators (jCzT9XFZ5bw)](https://www.youtube.com/watch?v=jCzT9XFZ5bw) — `@property`, getters, setters, deleters.
- *Benchmark*: Implement a multi-class inheritance hierarchy from memory in under 5 minutes without looking at documentation.

### Phase 2: Original OOP Project & Linear Algebra Kickoff (Sep 16 – Sep 22)
*Prove the OOP stuck by building an original project, push with architectural documentation, then open 3Blue1Brown.*
- **Task 1**: Build 1 original OOP project (e.g. Banking ledger, neural layer class simulator) in pure Python.
- **Task 2**: [3B1B Ch.1 — Vectors, what even are they?](https://www.youtube.com/watch?v=fNk_zzaMoSs) — Physics vs CS vs Math perspective.
- **Task 3**: [3B1B Ch.2 — Linear combinations, span, basis vectors](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) — $\hat{i}$ and $\hat{j}$ basis transformations.
- **Task 4 (Writing Checkpoint)**: Push OOP project to GitHub with a README explaining **why** you structured the classes this way (design rationale, not just what they do).

### Phase 3: Linear Algebra + NumPy Paired Code (Sep 23 – Oct 05)
*Compressed 13-day sprint. Every visual chapter gets re-implemented in NumPy on the same day.*
- **3B1B Ch.3**: [Linear Transformations & Matrices](https://www.youtube.com/watch?v=kYB8IZa5AuE) $\leftrightarrow$ `A @ x` matrix-vector product in NumPy.
- **3B1B Ch.4**: [Matrix Multiplication as Composition](https://www.youtube.com/watch?v=XkY2DOUCWMU) $\leftrightarrow$ `np.matmul(A, B)` ($AB \neq BA$).
- **3B1B Ch.5 & 6**: [The Determinant](https://www.youtube.com/watch?v=Ip3X9LOh2dk) $\leftrightarrow$ `np.linalg.det(A)` (geometric area scaling factor).
- **3B1B Ch.7**: [Inverse Matrices & Null Space](https://www.youtube.com/watch?v=uQhTuRlWM3E) $\leftrightarrow$ `np.linalg.inv()`, `np.linalg.solve()`.
- **3B1B Ch.8 & 9**: [Dot Products & Duality](https://www.youtube.com/watch?v=LyGKycYT2v0) $\leftrightarrow$ `np.dot()`, vector projections.
- **3B1B Ch.14**: [Eigenvectors and Eigenvalues](https://www.youtube.com/watch?v=PFDu9oVAE-g) $\leftrightarrow$ `np.linalg.eig()` (invariant axes).
- **Data Primer**: [10 Minutes to Pandas](https://pandas.pydata.org/docs/user_guide/10min.html) $\leftrightarrow$ DataFrames, indexing, groupby stats.
- **Writing Checkpoint**: Short writeup (blog or GitHub gist) explaining what the determinant and eigenvectors mean geometrically, in your own words.

### 🛑 Blackout 1: KRMU Mid-Term Examination (Oct 06 – Oct 17)
- **Mid-Term Exams**: Oct 13 – Oct 17 (Eligibility announced Oct 6).
- **Action**: ML Specialization is intentionally pushed to AFTER mid-terms. All side research pauses 100%. All evening slots (4:20 PM – 8:05 PM) switch to college syllabus revision. Target: 18+/20 internal marks to protect the 9.2 CGPA.

### Phase 4: Calculus Primer & Andrew Ng Course 1 (Oct 20 – Nov 02)
*Course 1 of Machine Learning Specialization (DeepLearning.AI on Coursera — free audit mode) with geometric Calculus primer.*
- **Calculus Primer**: [3B1B Essence of Calculus Playlist](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) — Ch. 1 "What is a derivative?", Ch. 2 "Derivative formulas through geometry", Ch. 3 "Visualizing the chain rule" (~40 min total). Directly equips you for gradient descent.
- **Enrollment**: [Machine Learning Specialization on Coursera](https://www.coursera.org/specializations/machine-learning-introduction)
- **Week 1**: Supervised learning, Linear Regression model, Cost function $J(w, b)$.
- **Week 2**: Multiple Linear Regression, multivariate gradient descent, learning rate $\alpha$, feature scaling.
- **Week 3**: Logistic Regression, sigmoid activation $\sigma(z)$, decision boundary, overfitting vs underfitting, L2 regularization.
- **From-Scratch Milestone**: Code linear and logistic regression gradient descent from scratch in pure NumPy without `scikit-learn`.
- **Writing Checkpoint**: Publish technical article / LinkedIn post: *"What I learned implementing gradient descent from scratch in NumPy"* (ML credibility building).

### Phase 5: Andrew Ng Course 2 & Backpropagation Calculus (Nov 03 – Nov 30)
*Course 2 of Machine Learning Specialization with formal 3B1B neural network calculus.*
- **Week 1**: Neural Network inference, dense layers, forward propagation in NumPy & TensorFlow ($A = g(XW + B)$).
- **Week 2**: Neural Network training, activation functions (ReLU, Sigmoid, Softmax), cross-entropy loss.
- **3B1B Dedicated Neural Networks Series**:
  - [Ch. 2: Gradient descent, how neural nets learn](https://www.youtube.com/watch?v=IHZwWFHWa-w)
  - [Ch. 3: What is backpropagation, really?](https://www.youtube.com/watch?v=Ilg3gGewQ5U)
  - [Ch. 4: Backpropagation calculus](https://www.youtube.com/watch?v=tIeHLnjs5U8) — formal chain rule connecting layer derivatives.
- **Writing Checkpoint**: Summarize backpropagation intuitively in your own words — the definitive test of whether Ch. 2–4 and chain rule mechanics truly landed.
- **Week 3**: Practical ML advice, bias vs variance diagnostics, train/val/test splits, precision/recall metrics.
- **Week 4**: Decision trees, information gain, entropy, Random Forests, XGBoost overview.
- **Research Reading**: [How to Read a Paper by Prof. S. Keshav (PDF)](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf) (Three-pass research paper methodology).

### 🛑 Blackout 2: KRMU Practicals & End-Term Exams (Dec 01 – Dec 24)
- **Practical Exams**: Nov 30 – Dec 04 · **Theory Finals**: Dec 07 – Dec 24.
- **Action**: Full university lock-in. Maintain morning gym 3–4 days/week as an essential physical outlet. Defend the 9.2 CGPA.

### Phase 6: Winter Break Probability & PyTorch Sprint (Dec 25, 2026 – Jan 10, 2027)
*17 full days with ZERO college classes. 6 to 8 hours daily deep block time.*
1. **StatQuest Probability Primer**: [StatQuest Fundamentals](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9) — Bayes' theorem, mean/variance, normal distribution (~2 hours total).
2. **StatQuest Maximum Likelihood Estimation**: [StatQuest MLE](https://www.youtube.com/watch?v=XepXtl9YKwc) — Closes the conceptual loop justifying Phase 4's logistic regression cost function.
3. **PyTorch Official Basics Tutorial**: [PyTorch Basics](https://pytorch.org/tutorials/beginner/basics/intro.html) (Tensors, Datasets, DataLoader, Autograd, `nn.Module`, Training Loop).
4. **CNN Implementation**: Build and train a Convolutional Neural Network on CIFAR-10 in PyTorch.
5. **Transformer Architecture**: Read Jay Alammar's [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/).
6. **Writing & Outreach Checkpoint**: Write 1-page summary of Illustrated Transformer + draft first personalized cold-email template to a professor in your chosen domain.
7. **Research Target Selection**: Browse [Papers With Code](https://paperswithcode.com/) to lock in your domain (Computer Vision, NLP/LLMs, or Graph ML).

### Phase 7: Even Semester & Summer Research Runway (Jan 11 – Apr 30, 2027)
*Translate autumn foundations and winter code into Summer 2027 research lab placement.*
- **Shortlist Faculty**: Shortlist 8–10 professors at IIT Bombay, IIT Delhi, IISc (CSA/CDS), and IIIT-H (CVIT) whose active research matches your Phase 6 focus domain.
- **Polish Academic CV & Portfolio**: Put 9.2 CGPA front-and-center alongside completed GitHub repositories: OOP architecture project, from-scratch NumPy regression, and PyTorch CNN.
- **Outreach Campaign**: Send first batch of personalized cold emails citing 1 recent paper from the professor's lab.
- **Monitor Fellowships**: Check application windows for IASc-INSA-NASI Summer Fellowship and IIT summer research programs (verify live portals directly; deadlines vary each year).
- **Second Portfolio Project**: Launch a larger, second deep learning project applying advanced architectures beyond CIFAR-10.

---

## ⚡ Key Features of the Tracker App

1. **Self-Contained & Zero Setup**:
   - Single file vanilla HTML5, CSS3, and modern ES6 JavaScript.
   - No servers or bundlers; works on any laptop, tablet, or phone.
2. **Phase Filtering & Dynamic Accordions**:
   - Filter instantly: *All Phases*, *Active Phase*, *Math & NumPy*, *Andrew Ng ML*, *Research Runway*, or *Exam Blackouts*.
3. **Interactive Task Checkboxes**:
   - Instant state toggle saved to browser `localStorage` (`aiml_prep_tracker_v1`).
   - Dynamic visual strikethroughs and live completion counters.
4. **Code Benchmarks Inside the App**:
   - Every phase includes high-yield code snippets and benchmarks you should be able to write from memory.
5. **Intuition & Notes Vault (📝)**:
   - Click the pencil icon next to any topic to record mathematical intuition, edge cases, or takeaways.
6. **Data Backup & Restore**:
   - 1-Click **`💾 Export Backup`** to download a `.json` snapshot of your notes and completed checkmarks.
   - 1-Click **`📂 Import Backup`** to restore your data on any device.

---

## 🔗 The 3-App Productivity System

Your `track` folder contains three specialized tools:

```
track/
├── schedule-tracker.html   <-- Daily Routine OS (Classes, Gym, Mess, Sleep)
├── aiml-tracker/
│   ├── index.html          <-- AI/ML Research Runway Tracker (This App)
│   ├── README.md           <-- Documentation & Roadmap Details
│   └── AI_CONTEXT.md       <-- Strategic Context for AI Assistants
└── dsa-tracker/
    ├── index.html          <-- DSA 365+ Master Tracker (230+ Curated Problems)
    ├── README.md           <-- DSA Syllabus Alignment
    └── AI_CONTEXT.md       <-- DSA Context & Schema
```
