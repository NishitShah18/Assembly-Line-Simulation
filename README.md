# Assembly Line Simulation

## Overview
This project is a simulation of an assembly line built using C++. The assembly line consists of multiple workstations, each holding specific stock items. Customer orders are processed as they move through the stations, and orders are filled if the requested items are in stock.

The line manager ensures that orders are transferred between workstations, and stations process orders one by one. Orders that are fully processed are marked as complete, while those that can't be fully filled due to stock shortages are considered incomplete.

The project is divided into three milestones, each building upon the functionality of the previous stage to provide a comprehensive learning experience in Object-Oriented Programming (OOP).

## Features
- Simulation of a dynamic assembly line with multiple stations
- Efficient management of customer orders and inventory
- Orders classified as "Complete" or "Incomplete"
- Stock management and queue processing at each station
- Object-Oriented design and modular codebase

## Technologies
- C++ (Object-Oriented Programming)
- Standard Template Library (STL)

## Requirements
- Git (to clone this repo)
- [GCC](https://gcc.gnu.org/)

## How to run?
1. Clone this repo - `git clone https://github.com/NishitShah18/Assembly-Line.git`
2. Open the repo in cmd/terminal
3. Execute the following command:<br>
`g++ -Wall -std=c++17 -g -o Project.exe CustomerOrder.cpp LineManager.cpp Station.cpp Utilities.cpp Workstation.cpp Main.cpp`<br>
`Project.exe Stations1.txt Stations2.txt CustomerOrders.txt AssemblyLine.txt`

### Please read [project overview](https://github.com/NishitShah18/Assembly-Line/tree/main/Project%20OverView) for more details about this program.
