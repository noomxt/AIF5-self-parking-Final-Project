# AIF5-self-parking-Final-Project
Markdown
# AIF5 Self-Parking Final Project

## Project Structure

- `self-parking-sim`: simulator and map assets
- `self-parking-user-algorithms`: student algorithm implementation

## Main Algorithm File

The main implementation is in:

```txt
self-parking-user-algorithms/student_planner.py
How to Run
1. Start simulator
PowerShell
cd self-parking-sim
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python demo_self_parking_sim.py
2. Start student agent
Open another terminal:
PowerShell
cd self-parking-user-algorithms
..\self-parking-sim\.venv\Scripts\Activate.ps1
python my_agent.py --host 127.0.0.1 --port 55556
Methods Used
Grid-based cost map
A* path planning
Line-of-sight path smoothing
Pure Pursuit control
Distance-based speed scheduling
