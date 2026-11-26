# Week 1 — Python and Programming Fundamentals

Welcome to the first week of AutoDrive!

Before building our self-driving car, we need to establish
a strong foundation in Python and the libraries that we
will use throughout this project.

This week focuses on learning through video tutorials,
hands-on coding and a small implementation exercise.

**Estimated time commitment: 6–8 hours**

---

## 1. Environment Setup

Install the following tools:

- [Python](https://www.python.org/downloads/)
- [VS Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/downloads/)

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Activate it on macOS/Linux:

```bash
source venv/bin/activate
```

Install the required libraries:

```bash
pip install numpy matplotlib
```

---

## 2. Python Fundamentals

### Video Resource

[Python Full Course for Beginners — freeCodeCamp](https://www.youtube.com/watch?v=rfscVS0vtbw)

Focus on the following sections:

| Topic | Timestamp |
|-------|-----------|
| Variables and data types | 15:06 |
| Working with numbers | 38:18 |
| Lists | 1:03:10 |
| Tuples | 1:18:57 |
| Functions | 1:24:15 |
| Return statements | 1:34:11 |
| Conditional statements | 1:40:06 |
| Dictionaries | 2:07:17 |
| While loops | 2:14:13 |
| For loops | 2:32:44 |
| Nested loops | 2:47:13 |
| Modules and pip | 3:28:13 |

You do not need to watch the entire course if you
are already familiar with Python.

### Concepts to Understand

- Variables and data types
- Conditional statements
- Loops
- Functions
- Lists, tuples and dictionaries
- Importing modules

### Why is this important?

We will use these concepts to implement vehicle movement,
driving logic, sensor readings and simulation loops.

---

## 3. Object-Oriented Programming (OOP)

### Video Resources

- [Classes and Instances — Corey Schafer](https://www.youtube.com/watch?v=ZDa-Z5JzLYM)
- [Python OOP Playlist — Corey Schafer](https://www.youtube.com/playlist?list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU)

Focus on the first two videos of the playlist.
Inheritance can be explored optionally.

### Concepts to Understand

- Classes and objects
- Constructors (__init__)
- Attributes and methods
- Instance variables
- The self keyword

### Why is this important?

Each car in our simulation will be represented as an
object with its own position, speed, direction, sensors
and fitness score.

Eventually, we will simulate multiple cars simultaneously,
each controlled by a different neural network.

---

## 4. NumPy

### Video Resource

[Complete NumPy Tutorial — Keith Galli](https://www.youtube.com/watch?v=GB9ByFAIAH4)

[Associated Practice Notebook](https://github.com/KeithGalli/NumPy)

### Concepts to Understand

- Creating NumPy arrays
- Array indexing and slicing
- Array arithmetic
- Shape and dimensions
- Basic mathematical operations
- Vectors and matrices
- Minimum, maximum and mean

### Why is this important?

NumPy will help us represent positions, directions,
sensor readings and numerical performance data.

Additional reference:

[NumPy Quickstart](https://numpy.org/doc/stable/user/quickstart.html)

---

## 5. Matplotlib

### Video Resource

[Matplotlib Tutorials — Corey Schafer](https://www.youtube.com/playlist?list=PL-osiE80TeTvipOqomVEeZ1HRrcEvtZB_)

Watch the first video on creating and customizing plots.

### Concepts to Understand

- Line plots
- Axis labels
- Plot titles
- Legends
- Displaying and saving graphs

### Why is this important?

During evolutionary training, we will use graphs to
visualize how the fitness of our self-driving cars
improves across generations.

Additional reference:

[Matplotlib Quickstart](https://matplotlib.org/stable/users/explain/quick_start.html)

---

## 6. Basic Mathematics for AutoDrive

### Video Resource

[Vectors — 3Blue1Brown](https://www.youtube.com/watch?v=fNk_zzaMoSs)

### Concepts to Revise

- Cartesian coordinate systems
- Vectors
- Angles and directions
- Sine and cosine
- Degrees and radians
- Distance between two points

Explore Python's built-in math module:

[Python Math Documentation](https://docs.python.org/3/library/math.html)

These concepts will help us implement car movement,
rotation and virtual radar sensors.

---

## 7. Git and GitHub

### Video Resource

[Git and GitHub for Beginners — freeCodeCamp](https://www.youtube.com/watch?v=RGOj5yH7evk)

### Concepts to Understand

- Creating a repository
- Cloning repositories
- git add
- git commit
- git push
- Writing a README

Every participant should maintain an individual GitHub
repository throughout the six-week project.

---

## Weekly Assignment

After completing the learning resources, attempt the
Week 1 assignment.

[View Assignment](./Assignment.md)

---

## Week 1 Completion Checklist

- [ ] Set up Python and the development environment.
- [ ] Understand Python fundamentals.
- [ ] Understand classes and objects.
- [ ] Perform basic NumPy operations.
- [ ] Create a plot using Matplotlib.
- [ ] Revise vectors and trigonometry.
- [ ] Create a GitHub repository.
- [ ] Complete and upload the weekly assignment.

---

## What's Next?

In Week 2, we will enter the world of game development
using Pygame and build our first manually controlled
virtual racing car!

**Learn. Build. Evolve. Drive.**