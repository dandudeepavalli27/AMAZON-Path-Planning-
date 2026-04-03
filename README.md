# AMAZON-Path-Planning-
Aim
To select the optimal path based on minimum traversal cost.
General Objective
To understand path planning algorithms used in autonomous robot navigation and how cost-based evaluation helps in selecting the most efficient route.
Specific Objective
To compare two paths:
Path A cost = 6
Path B cost = 4
and select the path with the minimum cost.
Dataset
Grid Path Planning Dataset
Source: PythonRobotics
Procedure
Input cost of Path A
Input cost of Path B
Compare both costs
Select path with minimum cost
Display result
Algorithm
Start
Input costs of Path A and Path B
If cost(A) < cost(B) → Select Path A
Else → Select Path B
Display result
Stop
Code Logic
if pathA < pathB:
    result = "Path A Selected"
else:
    result = "Path B Selected"

Industry Application
Path planning is used in:
Autonomous robots
Warehouse navigation
Delivery systems
Self-driving vehicles
Companies like Amazon use this in:
Warehouse robots
Route optimization
Logistics automation
Conclusion
Cost-based path selection helps robots choose the most efficient route, which is essential for real-time navigation and optimization.
