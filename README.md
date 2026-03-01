Dynamic Pathfinder - Instructions

====================================
1. Requirements
====================================

- Python 3.8 or newer

Tkinter is included with most Python installations.
No external libraries are required.


====================================
2. How to Check Python Installation
====================================

Open Command Prompt (Windows) or Terminal (Mac/Linux)
and type:

    python --version

or

    python3 --version

If Python is installed, it will show the version number.


====================================
3. How to Run the Program
====================================

Step 1: Open Command Prompt or Terminal

Step 2: Navigate to the folder containing the file:

    cd path_to_your_project_folder

Example:
    cd Desktop/DynamicPathfinder

Step 3: Run the file:

    python filename.py

OR (if python doesn't work)

    python3 filename.py


====================================
4. If Tkinter is Missing
====================================

If you get an error like:
    ModuleNotFoundError: No module named 'tkinter'

Install Tkinter using:

Windows:
    Usually included automatically with Python.
    Reinstall Python and make sure "tcl/tk and IDLE" is checked.

Linux (Ubuntu/Debian):
    sudo apt-get install python3-tk

Mac:
    Install Python from python.org


====================================
5. Controls
====================================

Mouse Controls:
- Left Click: Add/Remove Obstacle
- Right Click: Set Start Node
- Middle Click: Set Goal Node

Buttons:
- Start: Begin pathfinding
- Stop: Stop exploration
- Reset: Clear grid

Algorithms:
- A* Search
- Greedy Best First Search (GBFS)

Heuristics:
- Manhattan
- Euclidean
