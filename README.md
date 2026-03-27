# Hey I'm Andrew 

---

I’m a junior software engineer who seeks an opportunity to grow and have an impact on society by solving real-life problems and being a part of a bigger wheel.  

---

# My Experience so far 

---

## projects where I worked in a team environment 

### Graduation project: Monocular Vision Tracking System (October 2024-July 2025)

- **Description:**  
A pan and tilt head mounted with a camera designed for real-time tracking of moving objects to keep the center of the camera on the center of mass of the object.  

### My Role:
- Designed and implemented the Model by following a scientific paper, it’s a 1D array of vertices keeping the object within its perimeter via deformation and matching the object’s shape via adding/removing vertices.  
- Unit testing of the model to match the intended behavior from the paper.  
- System testing which revealed real-life problems in the model’s implementation from the scientific paper due to noise from the camera and the pan and tilt head. Solved these problems by engineering:  
  1. A control system that decides the next operation performed by the model.  
  2. Edges intersections’ detection and removal.  
  3. Failure detection and recovery.  
  4. Adding and optimizing parameters that control the model’s deformation and sensitivity to adding and removing new vertices.  
- Designed and used exterior tools and scripts to visualize problems.  

### Outcomes:
- Learned how to operate within a team:  
  1. Progress & issues report in my module and others’ modules.  
  2. How to integrate different software modules.  
- Exposed to agile process by making and refining a new version of my module every two weeks while adding new features along the way.  
- Participated in code reviews for my module and for others’ modules.  
- Solidified Software Development Life Cycle by being exposed to it in a real-life scenario.  

- **Technologies:** C++, Python  

- **GitHub repository** [https://github.com/Andrew20371160/The-Model](https://github.com/Andrew20371160/The-Model)

---

## Coursework project: Online File Storage Website

- **Description:**  
A website that allows users with accounts to store/retrieve files using a local network.  

### My Role:
- Leadership in designing the architecture of the whole system and dissecting it into manageable modules, each with its tasks, which helped my teammates start working on the project after a month of no progress, within a two-week period we developed and integrated our first version.  
- Designed and implemented a C++ server from scratch that keeps track of users’ accounts, handles authentication and file loading & uploading.  
- The server can handle up to 1000 users’ requests concurrently via implementing a thread pool, which consists of a listener thread and another 1000 working threads and solved concurrency problems that came up with it.  
- Designed the communication protocol between the flask side and the server side.  

### Outcomes:
- Learned the importance of the bigger picture and how system’s architecture affects the software engineering process.  
- Learned the importance of having bias for action in a real-life scenario by taking up a leadership opportunity beyond the scope of my experience for the sole purpose for the project to work, though I knew my credits wouldn’t be affected.  

- **Technologies:** C++, Pthreads, STL  

---

## Personal Projects

### 1. Matrix Library
- **Description:**  
An open-source C++ library that I built while studying MITOCW Linear Algebra course.  

- **Designed and Implemented:**  
  - Linear Algebra Algorithms ranging from matrix arithmetic, linear solvers to the four fundamental subspaces, matrix factorizations, fast Fourier transform (FFT).  
  - compression algorithms for matrices with different structures, which is outside the scope of the course, which decreases storage for triangular matrices down to 50%.  

- **Optimized:**  
  - algorithms’ runtime for these special matrices by iterating over non-zero elements only which decreases matrix multiplication running time down to 50%.  
  - performance and eliminated crashes for big matrices (1024x1024) via cache utilization by changing the underlying data structure from a a2D array to a 1D array with the same interface.  

- **GitHub repository:** [github.com/Andrew20371160/Matrix-Library ](https://github.com/Andrew20371160/Matrix-Library) 

---

### 2. Calculus Tree Library
- **Description:**  
An open-source C++ library that supports up to 21 mathematical functions that I built to know how expression trees work after listening to a 5-minute overview about them in a data structures lecture.  

- **Designed and implemented:**  
  - Expression tree generation from mathematical expression, a preprocessor that examines the mathematical expression for errors, expression evaluation, symbolic differentiation, numerical integration, vector calculus (gradient, curl, divergence).  

- **GitHub repository:** [github.com/Andrew20371160/Calculus-Tree-Library ](https://github.com/Andrew20371160/Calculus-Tree-Library) 

---

### 3. Digital Logic Design Environment
- **Description:**  
A C++ graph-based Digital Logic Design Environment inspired by an exam question in data structures final.  

- **Designed and implemented:**  
  - A graph data structure that represents gates with an additional wiring system for connecting outputs to inputs across the board.  
  - Console application that allows engineers to build, wire, and evaluate logic circuits made from primary logic gates.  
  - File persistence to save and reuse already built components with its wiring.  

- **GitHub repository:** [github.com/Andrew20371160/Digital-Logic-Design-Environment  ](https://github.com/Andrew20371160/Digital-Logic-Design-Environment)

---

### 4. Yes-No Decision Tree
- **Description:**  
A C++ framework for engineers to design interactive flows such as customer service scripts, diagnostic tools, educational quizzes, and decision-making aids.  

- **Designed and implemented:**  
  - A command-line application that supports multiple decision trees stored in a circular doubly linked list, with two usage modes:  
    1. Engineer Mode: create/edit/manage trees  
    2. User Mode: interact with existing trees (read-only operations)  
  - File persistence by saving & loading the decision trees in the same structure.  

- **GitHub repository:** [github.com/Andrew20371160/Yes-No-decision-tree](https://github.com/Andrew20371160/Yes-No-decision-tree)  

---

### 5. Database Creator
- **Description:**  
A C++ database creator that allows engineers to set up databases with their defined custom record schemas (unique key + typed fields) by adding a few lines of code.  

- **Designed and implemented:**  
  - A template-based binary search tree data structure.  
  - An abstraction layer on top of the binary search tree that lets engineers create their custom database schema.  
  - File persistence by saving databases with a bin file that includes starting index for each record so that when the database is loaded, it’s loaded in linear time instead of O(N log(N)).  

- **GitHub repository:** [github.com/Andrew20371160/Database-Creator](https://github.com/Andrew20371160/Database-Creator)  

---

## Technical Skills
- **Programming languages:** C++, Python.  
- **Frameworks/Libraries:** STL, Pthreads, NumPy, Matplotlib, Scikit-Learn.  
- **Version Control:** GitHub.  
- **Concepts:** Data structures, Algorithms, Object-Oriented Programming (OOP), Multithreading, Concurrency, Software Development Life Cycle, Unit testing, System testing, Code review, Code optimization, Agile process.  

---

## Education
**B.Sc. in Computer Engineering | Assiut University | 2020–2025**

---

## How to reach out 
- **Email:** andrew.k.saber@gmail.com  
- **LinkedIn:** [[https://www.linkedin.com/in/andrew-karam-saber-435b78228/]](https://www.linkedin.com/in/andrew-karam-saber-435b78228/)
