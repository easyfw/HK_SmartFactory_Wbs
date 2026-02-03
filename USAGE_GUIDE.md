# WBS Activity Management Sheet - Usage Guide

## Overview
This WBS (Work Breakdown Structure) Activity Management Sheet is designed to help manage the HK SmartFactory project activities, track progress, and ensure successful project delivery.

## Sheet Structure

### Column Descriptions

1. **WBS Code**: Hierarchical identifier for the work package (e.g., 1.0, 1.1, 2.0)
2. **Activity ID**: Unique identifier for each activity (e.g., ACT-001, ACT-002)
3. **Activity Name**: Short descriptive name of the activity
4. **Description**: Detailed description of what the activity involves
5. **Phase**: Project phase (Planning, Design, Implementation, Integration, Testing, Deployment, Maintenance)
6. **Start Date**: Planned start date for the activity
7. **End Date**: Planned completion date for the activity
8. **Duration (Days)**: Number of working days to complete the activity
9. **Status**: Current status of the activity
   - Not Started
   - In Progress
   - Completed
   - On Hold
   - Delayed
10. **Priority**: Importance level (Critical, High, Medium, Low)
11. **Assignee**: Person responsible for the activity
12. **Department**: Department or team responsible
13. **Completion %**: Percentage of work completed (0-100)
14. **Dependencies**: Activity IDs that must be completed before this activity can start
15. **Budget (USD)**: Allocated budget for the activity
16. **Actual Cost (USD)**: Actual expenditure to date
17. **Notes**: Additional comments, risks, or important information

## How to Use

### Opening the File
The sheet is provided in CSV format for maximum compatibility:
- **Excel**: File → Open → Select WBS_Activity_Management_Sheet.csv
- **Google Sheets**: File → Import → Upload file
- **LibreOffice Calc**: Open directly

### Updating Activities
1. Update the **Status** column as work progresses
2. Update **Completion %** regularly (weekly recommended)
3. Update **Actual Cost** as expenses are incurred
4. Add **Notes** for any issues, changes, or important updates

### Adding New Activities
1. Insert a new row
2. Assign the next sequential Activity ID (ACT-XXX)
3. Assign appropriate WBS Code based on hierarchy
4. Fill in all required fields
5. List any dependencies in the Dependencies column

### Tracking Progress
- **Green**: Activities on schedule and within budget
- **Yellow**: Activities with minor delays or budget concerns
- **Red**: Activities with significant delays or budget overruns

Use conditional formatting in Excel/Google Sheets:
- Completion % >= 100: Green
- Status = "Delayed" or "On Hold": Red
- Actual Cost > Budget: Red

### Dependency Management
- List all prerequisite activities in the Dependencies column
- Use comma-separated Activity IDs (e.g., "ACT-005,ACT-006,ACT-007")
- Ensure dependencies are resolved before starting an activity

### Budget Tracking
- Monitor the difference between Budget and Actual Cost
- Calculate cost variance: Actual Cost - Budget
- Negative variance indicates under budget
- Positive variance indicates over budget

## Best Practices

1. **Regular Updates**: Update the sheet at least weekly
2. **Clear Communication**: Use the Notes column for important updates
3. **Realistic Estimates**: Be honest about completion percentages
4. **Early Warning**: Flag delays or budget issues immediately
5. **Version Control**: Save dated versions (e.g., WBS_2026-02-03.csv)

## Project Context

This WBS is specifically designed for the HK SmartFactory project, which includes:
- **Hardware**: dsPIC33EV128 microcontroller integration
- **Software**: Factory management and monitoring systems
- **Integration**: Sensor networks and data collection
- **Deployment**: Production environment rollout

## Support

For questions or issues with the WBS Activity Management Sheet:
- Contact: Project Management Office
- Email: pmo@hksmartfactory.com
- Documentation: See README.md for project overview

## Version History

- v1.0 (2026-02-03): Initial release with 16 sample activities covering full project lifecycle
