REVIEW PACKET 

# System Overview
This project presents the design and simulation of a quadruped body capable of walking under load conditions. The system is modeled and analyzed in SolidWorks, integrating structural design, motion planning, and load analysis.
The objective is to ensure that the quadruped maintains stability, structural integrity, and controlled motion while carrying an external load.

# Design Specifications
Body Length: 250 mm
Body Width: 150 mm
Body Height: 155 mm
Leg Length: 120 mm
Walking Speed: 60 mm/s
Material Used: Aluminum 6061 alloy for load and base
            carbon Steel for links
Total Weight Applied: 58.1 N
# Load Calculation
Total Load (W) = 5.924 × 9.81 = 58.1 N

Load per leg: = Total Load / 4 = 58.1/4 = 14.05 N

# Motion Analysis Insight
Walking speed: 60 mm/s
Motion controlled using:
Path Mate → defines trajectory
Motors → drive joints

# Center of Mass (CoM)
Assumed at geometric center of body
Coordinates: (X, Y, Z)

X = 210.52 mm
Y = 60.93 mm
Z = 74.60 mm
The CoM lies near the geometric center, ensuring nearly uniform load distribution.

Explanation: The CoM is centrally located to ensure equal load distribution across all legs.

# Load Flow
Body → Hip Joint → Leg Links → Foot → Ground

Explanation: The load transfers from the body through joints into legs and finally to ground contact points.

# Simulation Setup
Fixed supports: Feet
Load applied: Top surface of body
Study type: Static
Mesh type: Standard mesh

# Results
Maximum Displacement: 0.046 mm
Stress Concentration Area: Leg-body joints
# Failure Scenarios
Joint failure due to high stress
Buckling of legs under high load
Uneven ground causing imbalance
# Actuator Consideration
Each joint must handle: Torque ≈ Force × distance

 T = F × L  = 14.5 × 0.12  = 1.74 Nm

# System-Level Understanding
This system behaves as a load distribution structure where:

Stability depends on CoM
Strength depends on joint design
Failure propagates from joints to entire structure
