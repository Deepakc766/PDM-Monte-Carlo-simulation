                                                                           Construction Project Scheduling Suite
Overview

This Python-based project demonstrates a progressive approach to construction project scheduling, starting from deterministic CPM and PERT methods and extending to an advanced probabilistic PDM using Monte Carlo simulation.

The suite allows users to:

Compute Critical Path Method (CPM) schedules with earliest/latest start and finish times

Estimate PERT-based task durations using optimistic, most likely, and pessimistic estimates

Simulate Precedence Diagram Method (PDM) projects with stochastic task durations, resource constraints, and risk events

Generate Gantt charts and perform sensitivity & critical path probability analysis

This project is suitable for construction management, project planning, and risk-aware decision making.

Features
1. CPM & PERT Module

Deterministic forward/backward pass calculations

Slack computation for each task

Identification of critical path

Optional PERT expected duration using optimistic, most likely, and pessimistic estimates

Gantt chart visualization for project schedule

2. Advanced PDM Monte Carlo Module

Handles 20+ tasks with mixed dependencies (Finish-to-Start, Start-to-Start, Finish-to-Finish, Start-to-Finish)

Models parallel workstreams and resource constraints (teams, equipment)

Includes dynamic risk events: weather, labor shortage, equipment failure

Monte Carlo simulation (5,000+ runs) for probabilistic project duration

Sensitivity analysis: identifies tasks with the largest impact on project duration

Critical path probability analysis: shows how often each task is on the critical path

Generates Gantt charts for sample project schedules
