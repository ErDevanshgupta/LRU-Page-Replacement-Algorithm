# LRU Page Replacement Algorithm Visualization

## Quick Navigation

- [Introduction](#introduction)
- [Overview](#overview)
- [Features](#features)
- [GLUT Library](#glut-library)
- [Getting Started](#getting-started)

## Introduction

This project offers a visual representation of the Least Recently Used (LRU) page replacement algorithm using OpenGL with GLUT (OpenGL Utility Toolkit) in C. The LRU algorithm is fundamental in operating systems for managing memory. It operates on the principle that the least recently used pages should be replaced when new pages need to be loaded into memory.

## Overview

LRU Page Replacement Algorithm Visualization provides an interactive way to understand the workings of the LRU algorithm. Users can input a sequence of 9 numbers representing page requests. The visualization then simulates the process of page requests, page faults, and page replacements, offering insight into how the LRU algorithm optimizes memory usage.

## Features

- **Front Page**: Displays project information, including the subject, authors, and guide, providing context for the visualization.
- **Interactive Input**: Users can input a sequence of 9 numbers representing page requests, allowing for customization and experimentation.
- **Real-time Visualization**: Renders the page request sequence and the state of memory (page frames) during the execution of the algorithm.
- **Animated Page Replacement**: Animates the process of page replacement, visually highlighting which pages are being replaced and when.
- **Customization Options**: Provides options to change the background and tile colors, enhancing the visualization experience.
- **User Interaction**: Supports mouse clicks and keyboard inputs for intuitive interaction with the visualization.

## GLUT Library

The GLUT (OpenGL Utility Toolkit) library is utilized to create graphical user interfaces in OpenGL applications. It provides a set of tools for window management, input handling, and event processing, simplifying the development of OpenGL-based projects.

## Getting Started

To run the visualization on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/username/lru-page-replacement-visualization.git
   ```

2. Navigate to the project directory:

   ```bash
   cd lru-page-replacement-visualization
   ```

3. Compile the code using a C compiler (e.g., GCC):

   ```bash
   gcc main.c -o lru_visualization -lglut -lGLU -lGL -lm
   ```

4. Run the compiled executable:

   ```bash
   ./lru_visualization
   ```

5. Follow the on-screen instructions to interact with the visualization.
# Input

![Screenshot 2024-05-02 212712](https://github.com/ErDevanshgupta/LRU-Page-Replacement-Algorithm/assets/110588013/6d26066a-7cc5-471e-a0f6-9a71e896c2ff)

# Output
![Screenshot 2024-05-02 212816](https://github.com/ErDevanshgupta/LRU-Page-Replacement-Algorithm/assets/110588013/bcc63010-e3c2-4eb5-9442-8730289864c9)
![Screenshot 2024-05-02 212828](https://github.com/ErDevanshgupta/LRU-Page-Replacement-Algorithm/assets/110588013/a56dab48-5287-4731-813a-55c736a7f64e)
![Screenshot 2024-05-02 212848](https://github.com/ErDevanshgupta/LRU-Page-Replacement-Algorithm/assets/110588013/b9cddf25-9869-4848-9ded-a2489896134d)
![Screenshot 2024-05-02 212909](https://github.com/ErDevanshgupta/LRU-Page-Replacement-Algorithm/assets/110588013/57bef177-2b4f-4014-adaa-147dfdabf42a)
![Screenshot 2024-05-02 212918](https://github.com/ErDevanshgupta/LRU-Page-Replacement-Algorithm/assets/110588013/db83b4d8-3dd9-4337-9e78-45f8e215f27a)
![Screenshot 2024-05-02 213019](https://github.com/ErDevanshgupta/LRU-Page-Replacement-Algorithm/assets/110588013/ccc9090c-b925-4b36-be2b-9ac82df96509)


