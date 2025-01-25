---
title: Rules
layout: default
nav_order: 2
description: "Understand the rules of Minesweeper before diving into the game."
permalink: /rules/
---

# 🎮 **Rules of Minesweeper**

Welcome to the world of **Minesweeper Simulation**! Before you start playing, make sure you’re familiar with the rules of the game. The following colorful guidelines will help you master the game and enjoy your experience. 🌟

---

## 🏆 **Game Objective**  

<div style="background-color: #e0f7fa; padding: 10px; border-left: 5px solid #00796b;">
The goal is simple:  
- <span style="color: #00796b; font-weight: bold;">Reveal</span> all the safe cells on the board without triggering any mines.  
- <span style="color: #d32f2f; font-weight: bold;">Flag</span> all the cells that you think contain mines.  
- Win by clearing all non-mine cells or lose if you uncover a mine!
</div>

---

## 🔍 **Rules Overview**

1. **Game Board**  
   <span style="color: #8e24aa;">The board is divided into a grid of cells:</span>  
   - Each cell is either a **mine** or **safe**.  
   - The number in a cell indicates how many mines are in the adjacent 8 cells.  

2. **Starting the Game**  
   Select a difficulty level:  
   - 🟢 <span style="color: #43a047; font-weight: bold;">Easy</span>: 9x9 grid with 10 mines.  
   - 🟡 <span style="color: #fbc02d; font-weight: bold;">Medium</span>: 16x16 grid with 40 mines.  
   - 🔴 <span style="color: #d32f2f; font-weight: bold;">Hard</span>: 16x30 grid with 99 mines.  

3. **Actions**  
   During your turn, you can:  
   - <span style="color: #1565c0; font-weight: bold;">Reveal a cell</span>:  
     - If it’s a mine, you lose the game. 💥  
     - If it’s a number, it shows the count of nearby mines.  
   - <span style="color: #2e7d32; font-weight: bold;">Flag a cell</span>:  
     - Mark suspected mine locations.  
   - <span style="color: #ef6c00; font-weight: bold;">Unflag a cell</span>:  
     - Remove a flag if you’re unsure about a cell.  

---

## 🔑 **Key Rules**

- <span style="color: #8e24aa;">Flagging a cell prevents accidental reveals.</span>  
- You cannot place a flag on a revealed cell.  
- The board's coordinates start at **(1,1)** in the bottom-left corner.  
- Revealing cells is recursive for zero-value cells, uncovering larger safe areas.  

---

## 💡 **Tips for Success**

<div style="background-color: #fff3e0; padding: 10px; border-left: 5px solid #ef6c00;">
- Start by revealing cells in a corner or edge for better visibility.  
- Use numbers strategically to deduce mine positions.  
- Be cautious—one wrong reveal, and it's game over!  
</div>

---

Ready to test your skills?  
<div style="text-align: center; margin-top: 20px;">
  <a href="#" class="btn btn-primary" style="background-color: #00796b; color: white; padding: 10px 20px; font-size: 18px;">Start Playing Now</a>
</div>
