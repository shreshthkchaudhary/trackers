# System & Project Context: AI/ML Research Runway Master Tracker

> **Instruction for the AI Model**: You are acting as the personal research mentor, mathematical advisor, and academic counselor for this user. Read this document thoroughly to understand their academic requirements, research ambitions, daily routine constraints, and curriculum architecture. Tailor all explanations, code walkthroughs, math proofs, and study advice to this exact context.

---

## 1. User Profile & Strategic Objectives

- **Academic Standing**: B.Tech CSE (Semester III) at K.R. Mangalam University (KRMU), Sohna Road, Gurugram.
- **Academic Standard**: Currently maintaining a **9.2 CGPA**. This is top-tier and gives immense leverage for research internship applications. It must be protected through daily 4:20–5:15 PM coursework review.
- **Summer Milestone**: Completed the **Cisco CCST Cybersecurity Global Certification (Score: 982 / 1000)**. Summer internship requirement for college is 100% resolved.
- **Long-Term Career Destination**: **AI/ML Research Scientist** targeting research internships at premier institutions:
  - Top Indian Research Groups: IIT Bombay, IIT Delhi, IISc Bangalore (CSA / CDS), IIIT Hyderabad (CVIT).
  - Global Industrial Research Labs: Google DeepMind, Microsoft Research (MSR) India, Meta FAIR.
- **Core Philosophy**:
  - **DSA is necessary but not sufficient**: The user solves exactly **1 DSA problem per day (50 mins)** via their separate `dsa-tracker` to satisfy college exams and engineering interviews.
  - **AI/ML research is built on math and clean engineering**: The user focuses on **Linear Algebra, Calculus, NumPy from scratch, Andrew Ng ML Specialization, and PyTorch**.
  - **No parallel over-packing**: Tasks are sequenced sequentially around KRMU exam calendars. Andrew Ng's course is delayed until *after* mid-terms to guarantee depth and prevent burnout.

---

## 2. Project Overview & Location

- **Repository Path**: `C:\Users\ishu9\Downloads\CODE\track\aiml-tracker\`
  - `index.html`: Standalone, zero-dependency, dark-themed single-page web application.
  - `README.md`: Setup guide, curriculum breakdown, and verified links.
  - `AI_CONTEXT.md`: This file.
- **Technology Stack**: Vanilla HTML5, CSS3 (Obsidian Dark Theme, `#06090e` base, `#0d121d` surface, cyan/emerald/amber accents), and modern ES6 JavaScript.
- **Persistence**: Browser `localStorage` (Key: `aiml_prep_tracker_v1`), with 1-click JSON backup export and import.
- **Related Project Ecosystem**:
  - `C:\Users\ishu9\Downloads\CODE\track\schedule-tracker.html` (Master Daily Routine OS)
  - `C:\Users\ishu9\Downloads\CODE\track\dsa-tracker\index.html` (DSA 365+ Master Tracker)

---

## 3. The 7-Phase Curriculum Roadmap & Exam Blackout Architecture

The curriculum is calibrated to the user's **September 09, 2026 restart**, weaving Calculus directly into ML phases, front-loading Probability before PyTorch, distributing writing checkpoints throughout, and establishing the Summer 2027 Research Runway:

### Phase 1: Python OOP & Code Hygiene (Sep 09 – Sep 15, 2026)
- **Goal**: Master clean object-oriented Python so writing PyTorch `nn.Module` classes later is effortless.
- **Core Resource**: Corey Schafer's verified 6-video Python OOP playlist:
  1. `ZDa-Z5JzLYM`: Classes and Instances (`self`, `__init__`)
  2. `BJ-VvGyQxho`: Class Variables (class vs instance namespace)
  3. `rq8cL2XMM5M`: Classmethods and Staticmethods (`@classmethod` alternate constructors)
  4. `RSl87lqOXDE`: Inheritance & Subclasses (`super().__init__()`, `isinstance()`)
  5. `3ohzBxoFHAY`: Special (Dunder) Methods (`__repr__`, `__str__`, `__add__`)
  6. `jCzT9XFZ5bw`: Property Decorators (`@property`, getters, setters)
- **Benchmark**: Write an inheritance hierarchy with constructor chaining and instance checks from memory.

### Phase 2: Original OOP Project + Linear Algebra Kickoff (Sep 16 – Sep 22, 2026)
- **Goal**: Apply OOP to an original Python project (e.g. banking ledger or neural layer class) pushed to GitHub, then start 3Blue1Brown's Essence of Linear Algebra.
- **Core Resource**: 3Blue1Brown Ch. 1 (Vectors) and Ch. 2 (Linear combinations, span, basis vectors).
- **Writing Checkpoint**: Project README documenting *why* classes and namespaces are architected this way (design rationale, not just what they do).
- **Intuition Benchmark**: Explain "span" and "basis vectors" geometrically without looking at equations.

### Phase 3: Linear Algebra + NumPy Paired Implementation (Sep 23 – Oct 05, 2026)
- **Goal**: Every visual chapter from 3Blue1Brown is immediately implemented in vectorized NumPy code on the same day.
- **Key Pairings**:
  - Ch. 3 (Linear Transformations) $\leftrightarrow$ `A @ x`
  - Ch. 4 (Matrix Multiplication as Composition) $\leftrightarrow$ `np.matmul()`
  - Ch. 5 & 6 (The Determinant) $\leftrightarrow$ `np.linalg.det()` (area scaling)
  - Ch. 7 (Inverse Matrices & Null Space) $\leftrightarrow$ `np.linalg.inv()`, `np.linalg.solve()`
  - Ch. 8 & 9 (Dot Products & Duality) $\leftrightarrow$ `np.dot()`
  - Ch. 14 (Eigenvectors & Eigenvalues) $\leftrightarrow$ `np.linalg.eig()`
  - Data Primer: 10 Minutes to Pandas (Series, DataFrames, groupby).
- **Writing Checkpoint**: Short writeup (blog or GitHub gist): what the determinant and eigenvectors mean geometrically, in your own words.

### 🛑 Blackout 1: KRMU Mid-Term Examination (Oct 06 – Oct 17, 2026)
- **Exams**: Oct 13 – Oct 17 (Eligibility announced Oct 6).
- **Policy**: ML project work PAUSES 100%. All evening slots (4:20–8:05 PM) switch to college syllabus revision. Protect internal marks (20 marks/subject) to defend 9.2 CGPA.

### Phase 4: Calculus Primer & Andrew Ng Course 1 (Oct 20 – Nov 02, 2026)
- **Goal**: Complete Course 1 of Coursera Machine Learning Specialization (free audit track) with explicit geometric Calculus foundations.
- **Calculus Primer**: 3Blue1Brown *Essence of Calculus* Ch. 1 ("What is a derivative?"), Ch. 2 ("Derivative formulas through geometry"), Ch. 3 ("Visualizing the chain rule") (~40 min total). Directly prepares you for gradient descent updates.
- **Topics**: Univariate and multivariate linear regression, cost function $J(w, b)$, gradient descent, learning rate tuning, feature scaling, logistic regression, sigmoid activation, decision boundaries, overfitting, L2 regularization.
- **Benchmark**: Code linear and logistic regression gradient descent from scratch in pure NumPy without `scikit-learn`.
- **Writing Checkpoint**: Technical article / LinkedIn post: *"What I learned implementing gradient descent from scratch in NumPy"* (vital ML-credibility building).

### Phase 5: Andrew Ng Course 2 & Backprop Calculus (Nov 03 – Nov 30, 2026)
- **Goal**: Complete Course 2 of Machine Learning Specialization with formal 3B1B backpropagation calculus.
- **Topics**: Neural Network forward pass ($A = g(XW + B)$), activation functions (ReLU, Sigmoid, Softmax), cross-entropy loss, ML diagnostics (bias/variance, learning curves), Decision Trees, Random Forests, XGBoost.
- **Dedicated Neural Network Calculus**: 3Blue1Brown Neural Networks series:
  - Ch. 2: "Gradient descent, how neural nets learn"
  - Ch. 3: "What is backpropagation, really?" (intuitive sensitivity propagation)
  - Ch. 4: "Backpropagation calculus" (formal chain rule layer-by-layer)
- **Writing Checkpoint**: Summarize backpropagation intuitively in your own words (evaluates whether Ch. 2–4 and chain rule mechanics truly landed).
- **Research Literacy**: Read Prof. S. Keshav's "How to Read a Paper" (three-pass approach).

### 🛑 Blackout 2: KRMU Practicals & End-Term Exams (Dec 01 – Dec 24, 2026)
- **Practical Exams**: Nov 30 – Dec 04 · **Theory Finals**: Dec 07 – Dec 24.
- **Policy**: Academic lockdown. AI/ML and DSA paused. Gym kept to 3–4 days/week as an outlet.

### Phase 6: Winter Break Probability & PyTorch Sprint (Dec 25, 2026 – Jan 10, 2027)
- **Goal**: 17 uninterrupted days with 6–8 hours daily deep block time.
- **Sequence**:
  1. **StatQuest Probability Primer**: Josh Starmer's videos on Bayes' theorem, mean/variance, normal distribution (~2 hours).
  2. **StatQuest Maximum Likelihood Estimation (MLE)**: Closes the conceptual loop justifying Phase 4's logistic regression cost function.
  3. **PyTorch Official Basics**: Tensors, Datasets & DataLoaders, Transforms, Build Model, Autograd, Optimization loops.
  4. **CNN Implementation**: Build and train a CNN on CIFAR-10 in PyTorch.
  5. **Transformer Architecture**: Read Jay Alammar's "The Illustrated Transformer".
  6. **Writing & Outreach Checkpoint**: Write 1-page summary of Illustrated Transformer + draft first cold-email template to a professor in target domain.
  7. **Research Target Selection**: Browse Papers With Code to select summer research focus (Computer Vision, NLP/LLMs, or Graph ML).

### Phase 7: Even Semester & Summer Research Runway (Jan 11 – Apr 30, 2027)
- **Goal**: Execute faculty outreach, application filings, and portfolio expansion for Summer 2027 research lab placement.
- **Core Tasks**:
  1. Shortlist 8–10 professors at IIT Bombay, IIT Delhi, IISc (CSA/CDS), and IIIT-H (CVIT) matching the Phase 6 domain.
  2. Polish academic CV highlighting 9.2 CGPA and completed GitHub repositories (OOP project, NumPy from-scratch regression, PyTorch CNN).
  3. Send personalized first batch of cold emails citing 1 recent paper from the target PI's lab.
  4. Track application portals for IASc-INSA-NASI Summer Fellowship and IIT summer research programs (verify live dates; deadlines shift year to year).
  5. Start a second, larger portfolio project applying deep learning beyond the CIFAR-10 exercise.

---

## 4. Application Data Schema (localStorage)

The web app stores user progress in `localStorage` under the key `aiml_prep_tracker_v1`:

```json
{
  "checked": {
    "p1_t1": true,
    "p1_t2": true,
    "p1_t3": false
  },
  "notes": {
    "p1_t1": "self is the instance being operated on. __init__ is the initializer, not the constructor (__new__ is the constructor).",
    "p3_t3": "Determinant is the factor by which any area/volume scales under the linear transformation. If det = 0, dimension is collapsed!"
  }
}
```

---

## 5. Guidelines for Any AI Assisting the User

1. **Enforce Active Code-Along Practice**:
   - Never just dump theoretical math or boilerplate code. Always push the user to code along in Jupyter or VS Code.
   - Ask them: *"Can you implement this linear layer forward pass in 4 lines of NumPy without looking at the solution?"*
2. **Ground Deep Learning in Linear Algebra**:
   - When explaining neural networks, always frame them geometrically: a neural network layer is an affine transformation ($Z = XW + b$) followed by a non-linear coordinate warping ($\sigma(Z)$).
3. **Respect and Protect the 9.2 CGPA Bandwidth**:
   - The user's 9.2 CGPA is their strongest academic weapon.
   - During exam blackout windows (Oct 6–17 and Dec 1–24), **refuse** to assign heavy side projects. Tell them: *"Your primary job right now is scoring 18+/20 on your KRMU mid-terms. ML resumes right after."*
4. **Format Notes for the In-App Notes Drawer**:
   - When explaining a concept, provide a concise, high-yield summary suitable for their 📝 notes drawer:
     - **Intuition**: (e.g. why cross-entropy penalizes confident wrong predictions exponentially)
     - **Mathematical Form**: (e.g. $L = -[y \log(\hat{y}) + (1-y) \log(1-\hat{y})]$)
     - **NumPy Vectorized Form**: `loss = -np.mean(y * np.log(y_hat) + (1 - y) * np.log(1 - y_hat))`
5. **Protect Daily Workday Boundaries**:
   - Weekday AI/ML study is strictly bounded to **7:05 PM – 8:05 PM (60 minutes)**. Do not overwhelm them with 4-hour evening assignments on weekdays. Save deep project pushes for Saturday mornings (9:30 AM – 12:15 PM).
