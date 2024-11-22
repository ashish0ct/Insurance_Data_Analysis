# Insurance Data Analysis

## Overview
This repository contains an analysis of insurance data using Microsoft SQL Server and Power BI. The project demonstrates data visualization, role-based access control, and dashboard creation for insurance policy management.

## Project Structure
- `InsuranceData.csv` - Raw insurance data
- `Insurance_Data_Analysis.pbix` - Power BI report file
- `Page 1.png` - Screenshot of main dashboard
- `Page 2.png` - Screenshot of detailed policy view
- `learning.txt` - Documentation of learning outcomes

## Features
- Interactive dashboards showing:
  - Premium Amount by Policy Type
  - Count of Active/Inactive Policies
  - Number of Claims by Claim Status
  - Claim Amount by Age Group
  - Detailed policy information

## Technical Implementation
1. **Data Storage**
   - Created database "Insurancedb" in Microsoft SQL Server
   - Imported CSV data using flat file import

2. **Power BI Implementation**
   - Connected to SQL Server database
   - Created comprehensive data visualizations
   - Implemented drill-through filters
   - Set up role-based security

3. **Advanced Features**
   - Drill-through functionality from policy type to detailed views
   - Role-based access control (e.g., Travel role for Travel managers)
   - Scheduled data refresh using On-premises data gateway
   - Dashboard creation in Power BI service

## Key Visualizations
- Premium distribution across policy types
- Active vs. Inactive policy comparison
- Claims status analysis
- Age-based claim amount trends
- Detailed policy records view

## Learnings
- SQL Server database management
- Power BI desktop and service features
- Data refresh scheduling
- Role-based security implementation
- Drill-through filter configuration
- Dashboard vs. Report distinctions

## Dashboard Metrics
- Total Premium Amount: 5.98M
- Total Coverage Amount: 600.55M
- Total Claim Amount: 16.91M
- Policy Distribution across Auto, Health, Travel, Life, and Home insurance types

## Future Enhancements
- Additional drill-through capabilities
- More detailed demographic analysis
- Enhanced role-based access controls
- Automated reporting schedules

## Tools Used
- Microsoft SQL Server Management Studio
- Power BI Desktop
- Power BI Service
- On-premises data gateway
