# Page-Replacement-Algorithm-Simulator
Project Overview
This project is a simulator for page replacement algorithms (FIFO, LRU, and Optimal) developed as part of the Operating Systems course (CSE316). The tool allows users to visualize and compare different page replacement strategies through an interactive GUI.
Modules

Page Reference Input Module

Allows users to enter custom page reference strings
Supports dynamic frame size configuration


Algorithm Simulation Module

Implements three page replacement algorithms:

First-In-First-Out (FIFO)
Least Recently Used (LRU)
Optimal Page Replacement




Visualization Module

Generates graphical comparisons of page fault rates
Provides cumulative page fault timeline
Displays algorithm performance metrics



Technologies Used

Programming Language: Python
Libraries:

Tkinter (GUI)
Matplotlib (Visualization)
NumPy (Optional data manipulation)



Installation Requirements

Python 3.x
tkinter
matplotlib

# Install dependencies
pip install matplotlib
# Note: tkinter typically comes pre-installed with Python

How to Run

python page_replacement_simulator.py

Usage Instructions

Enter page reference string (space-separated integers)
Specify frame size
Click "Simulate" to view results
Analyze page fault comparisons and timeline

Future Scope

Add more page replacement algorithms
Enhance visualization options
Implement advanced performance metrics
Create web/mobile versions

References

Operating Systems Concepts by Silberschatz
Computer Systems: A Programmer's Perspective

Contributing

Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

License
Distributed under the MIT License. See LICENSE for more information.
