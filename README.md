# Drone-Fleet-Management-System
Systems analysis and design project (INFO 380): a Drone Fleet Management System for wind turbine inspections, with AI defect detection, dashboard mockups, data flow diagram, adoption plan, and roadmap.

## Overview
 
Windtech Innovation inspects its wind turbines through manual technician visits. This project proposes a **Drone Fleet Management System (DFMS)**: autonomous AI-powered drones that inspect turbines, with a centralized dashboard for reviewing footage, monitoring emissions, and forecasting maintenance needs.
 
This is a systems analysis and design project. It covers the problem analysis, proposed solution, data flow design, dashboard mockups, adoption plan, roadmap, and risk planning. It is a design proposal and was not built or deployed.
 
## Problem
 
Relying entirely on manual inspections leads to:
 
- **Safety risks** for crew members working in hazardous environments
- **Operational challenges:** inconsistent data, difficulty meeting FAA regulations, and no real-time analytics
- **Higher carbon emissions** from technicians driving to inspection sites
## Proposed Solution
 
- Deploy autonomous AI-powered drones for routine turbine inspections
- Run real-time onboard AI to detect cracks, corrosion, and hub wear
- Use a centralized dashboard to monitor drone performance and inspection history
- Show instant alerts when emission rates exceed safe thresholds
**Workflow:** drone footage capture, real-time onboard defect detection, centralized data, instant issue notifications, and reduced site visit time.
 
## Dashboard Design
 
The mockups were designed around three pages, each with annotated features.
 
### 1. Real-Time Monitoring
- Footage viewer with playback controls and a comment box for technicians to add findings the AI misses
- AI insights and advised actions (for example, blade replacement)
- Technician sign-up for review and maintenance tasks, with a required number of technicians per task
- Drone list with color-coded review status (red: not yet reviewed, yellow: under review, green: reviewed)
- Stream performance metrics, including dropped streams, which tie to the acceptance criterion of under 2%
- Per-drone task checklist, search, sort, and a light/dark mode toggle
  
### 2. Sustainability Monitoring
- Real-time carbon emission map with GPS location, timestamp, and optimized drone flight routes
- Emission alerts when levels exceed 50 ppm, requiring acknowledgment and team dispatch
- Monthly sustainability report comparing drone routes with traditional vehicle routes
- Energy consumption and drone maintenance emissions tracking
- Wildlife impact incidents and noise pollution alerts, tied to goals of fewer than 5 noise complaints per year and measured noise below 20 decibels

### 3. Inventory Forecast Monitoring
- Monthly inventory log comparing predicted and actual part usage, with accuracy and stock status
- Manage Orders and Update Log actions for technicians
- Predictive maintenance log with predicted failure dates and urgency levels
- Safety incident report log and routine maintenance task details

*All numbers shown in the mockups are illustrative placeholder values, not real results.*

## System Design
 
The data flow diagram models the system with:
 
- **External entities:** Technicians, Operations Manager, Drone, Environmental Review Board
- **Processes:** Login, Add/Edit Turbine Details, Upload Drone Footage, Request Report, Add/Resolve Issues, Search Archive
- **Data stores:** Drone, Users, Turbine, Drone Footage, Issue, Emissions/Energy, and Archive tables

## Benefits
 
| Area | What it provides |
|---|---|
| Report systems | Worker, drone, and turbine reporting |
| Dashboard features | Drone overview, turbine overview, AI insights |
| Alerts and monitoring | Weather forecast, environmental impact, drone fleet monitoring |
| Logs and predictions | Maintenance logs, predictive maintenance, safety logs |
 
## Adoption Strategy
 
Training was tailored to each user group:
 
| Group | Approach |
|---|---|
| Wind turbine technicians | In-person demos on reviewing, claiming tasks, documenting fixes, and escalating |
| Environmental analysts | Training videos on the Sustainability Monitoring page and generating reports |
| Operations managers | Training videos on tracking efficiencies and managing drones, turbines, technicians, and vehicles |
| Safety officers | Video tutorial on reviewing and resolving incidents and generating reports |
| IT analysts | Detailed documentation, design documents, and a list of tools and frameworks |
| Everyone | Slack support channels with experts on rotation, an FAQ, and weekly surveys and check-ins for the first month |
 
## Roadmap
 
| Quarter | Focus | Example milestones |
|---|---|---|
| Q1 | Foundation and safety first | Safety training for 100% of maintenance staff, wind turbine output dashboard, weekly inspection logs with compliance tracking |
| Q2 | Systems activation and optimization | Issue tracking dashboard, environmental impact monitoring, begin measuring and reducing employee travel miles and emissions |
| Q3 | Intelligence, automation, and uptime | 70% automation of routine inspection tasks, over 95% system uptime, 30% less downtime from delayed maintenance |
 
## Risks and Contingency Plans
 
| Risk | Impact | Contingency |
|---|---|---|
| Severe weather | Unsafe for drones and technicians, inspection delays | Real-time weather updates and rescheduling unsafe launches |
| FAA non-compliance | Fines and operations shutdowns | Thorough regulation review and expert review of flight plans |
| Cybersecurity threats | Data breaches, compromised inspections, drone hijacking | Multi-factor authentication, firewalls, incident response plans |
| Supply chain delays | Downtime from missing parts | Advance hardware delivery and buffer inventory |
 


 
