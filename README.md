# Project-6---Reeborg-s-World-Maze-Solver

This is a beginner-to-intermediate Python project built as part of my 100 Days of Code challenge.

The goal of this project is to guide a robot through different maze environments and successfully reach the goal using logical rules.

**Project Overview**

This project uses Reeborg’s World, a visual programming environment where a robot must navigate mazes.

The robot can:

Move forward

Turn left or right

Sense obstacles in front or to the right

The program then:

Follows a consistent navigation strategy (right-hand rule)

Adapts to different maze layouts

Stops once the robot reaches the goal

**Why this project exists**

This project represents a major shift from writing linear scripts to solving open-ended problems.

I learned how to:

Think algorithmically

Translate real-world logic into code

Handle unknown environments dynamically

Apply looping and conditional logic together

**What I learned**

How to use while loops to continue actions until a condition is met

How to use condition checks like front_is_clear() and right_is_clear()

How to combine multiple conditions to control behavior

How to write reusable helper logic (turning right using turn_left)

How maze-solving algorithms work in principle

**How the code works (step-by-step)**

Move forward until the robot hits a wall

Turn left to begin navigating the maze

Repeat actions until the goal is reached

If the right side is clear, turn right and move

If the front is clear, move forward

Otherwise, turn left to find a new path

**Example Output**

The robot navigates through the maze visually and stops once it reaches the goal flag in Reeborg’s World.
