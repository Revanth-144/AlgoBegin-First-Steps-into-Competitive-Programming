# 📢 Week 8 Project – PathQuest Lite: CP Maze Solver Challenge 🧩🧠

Hey everyone!

We’ve made it to **Last Week of our Python CP Bootcamp! 🚀** Now it's time to put everything we’ve learned into action with a hands-on project challenge that simulates real-world competitive programming conditions.

## Introducing: **PathQuest Lite**
A CP-style AI that solves randomized mazes using optimal strategies and **only allowed Python libraries**. This is your chance to code like you’re in a real contest! 🏆🐍

---

## 🔍 **Project Overview**

You'll build a **maze-solving bot** that navigates from a **start (S)** to an **end (E)** point with the shortest possible energy cost.

Maze components:
- **Traps (T)** – cost extra energy
- **Monsters (M)** – deduct health/energy
- **Empty paths (.)** – normal movement
- **Optional:** Portals for bonus moves

Your solver must use **Dijkstra’s algorithm** (or any CP-valid optimal strategy).

---

## ✅ **What You’ll Practice**
- Efficient I/O and Input Parsing with `sys.stdin`
- Contest-style problem reading
- Choosing between **BFS/Dijkstra** based on the grid
- Handling edge cases (isolated S/E, dead-ends)
- Usage of only **CP-Approved Libraries**:  
  `heapq`, `collections`, `bisect`, `itertools`, `functools`, `math`, `string`, `random`
- Optimization using memoization (`@lru_cache`)
- Timing code to avoid TLEs

---

## 🏁 **Project Tasks**
- [x] Generate random mazes with monsters and traps
- [x] Implement a solver using Dijkstra’s algorithm
- [x] Compute & print minimum cost to reach the end
- [x] Score multiple testcases & simulate contest runs
- [ ] *(Optional)* Strategy comparison: BFS vs Dijkstra

---

## 🎯 **Bonus Challenges**
- ⚡ Portals (P): teleport between pairs
- ⚡ Track monsters encountered
- ⚡ Scoring leaderboard for multiple runs
- ⚡ Utility functions for input parsing templates

---

## 📚 **Recommended Setup**
- Single Python file with:
  - `main()` to run all logic
  - Input via `sys.stdin`
  - Modular functions for solver, parser, generator

---

## 📖 **Contest Simulation Tips**
- Test with **5+ randomized mazes** (vary size + seed)
- Score based on **path cost & monster hits**
- Time your solution to **simulate TLE**

---

## 🧠 **Key Takeaways**
- CP-style structured solutions
- Mastery of Python libraries under constraints
- Confidence for **Codeforces, Leetcode**, etc.

💡 **Pro Tip:** This isn’t just a project—it’s your mini-contest. Compete, upsolve, optimize, and win against yourself!

---

Let’s close SOC with a bang — not just as coders, but as **contest-ready warriors! ⚔💻🐍**

**Happy coding!**
