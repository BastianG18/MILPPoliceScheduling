1. Project Overview
This research develops an optimization-based police scheduling system using Mixed Integer Linear Programming (MILP)
to generate efficient and fair duty rosters. The model assigns police officers to shifts while considering:

Operational staffing requirements
Officer shift preferences
Fatigue management and rest regulations
Fair workload distribution
Legal and organizational scheduling constraints

Traditional manual scheduling often leads to inefficiencies, dissatisfaction, overtime imbalance, and fatigue-related performance decline. 
This study proposes a mathematical decision-support framework to improve scheduling quality.

2. Research Objectives
The main objectives of this study are:
Develop a MILP model for police shift assignment.
Integrate officer preferences into scheduling decisions.
Reduce fatigue accumulation through rest-aware constraints.
Improve fairness in workload allocation.
Compare optimized schedules with conventional/manual schedules.

4. Problem Description
Police departments typically operate under 24/7 service requirements, requiring officers to work across multiple shifts such as:
Morning Shift, Evening Shift, and Night Shift

The scheduling problem becomes complex because:

Different officers have different preferred shifts/days.
Consecutive night shifts may increase fatigue.
Minimum rest periods must be respected.
Certain roles require qualified personnel.
Staffing levels must be met every shift.

This creates a large-scale combinatorial optimization problem suitable for MILP.

4. Methodology
This problem is defined as a NP-hard problem because of the dimensionality size and computation complexity, especially with constraints as below:
1. Staffing Requirements
2. Each shift must have sufficient officers.
3. Single Shift per Day
4. Each officer can work at most one shift daily.
5. Rest Period Rules
6. Minimum rest time between shifts must be maintained.
7. Maximum Consecutive Working Days
8. Limit excessive continuous workdays.
9. Night Shift Restrictions
10. Limit consecutive night assignments.
11. Qualification Constraints
12. Certain shifts require specialized personnel.
13. Fair Workload
14. Total assignments distributed equitably.

5. Expected Contributions

This research contributes by:
1. Improving officer wellbeing
2. Enhancing operational readiness
3. Reducing fatigue risk
4. Increasing fairness and satisfaction
5. Supporting data-driven workforce management

6. Future Extensions
Possible future developments:
1. Multi-station coordination
2. AI-based Optimization or Metaheuristic Approachs
3. Robust optimization under uncertainty
