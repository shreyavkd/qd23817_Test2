# Minimal Disks Simulation
### Generated by Doxygen 1.13.2

## Overview
The code simulates the random motion of hard disks inside a box with hard walls.

---

## File Descriptions
- **disk.h**: Defines 'Disk' class for individual disks.
- **system.h**: Defines 'System' class modelling the motion of the disks.

- **disk.cpp**: Initialises member functions of 'Disk' class.
- **system.cpp**: Initialises member functions of 'System' class.
- **main.cpp**: Beginning of code execution to run the simulation.

- **view.py / view.ipynb**: Used to visualise the system.

- **.gitignore**: Lists files to be ignored while uploading (due to redundancy).

- (extra) **Makefile**: Used to make execution more compact.
---

## Cloning from Git
	git clone https://github.com/shreyavkd/qd23817_Test2

---

## Execution Instructions
- **Compilation**:
	g++ main.cpp system.cpp disk.cpp -o simulation

- **Execution**:
	./simulation
	(or)
	./simulation.exe

- **Visualisation**:
	python view.py
	(or alternative versions of python ex. python3)

---

### Optional: Using "make"
- **Compilation**:
	make

- **Execution**:
	make run

- **Visualisation**:
	python view.py
	(or alternative versions of python ex. python3)

---

#### Note:
In case of cloning from GitHub repository, create folder 'confs' using bash command
mkdir confs

