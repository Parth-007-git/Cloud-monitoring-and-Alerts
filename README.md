# Cloud-monitoring-and-Alerts

**COMPANY**: Codtech IT Solutions Private Limited

**NAME**:Parth Girish Kulkarni

**INTERN ID**:CTIS3903

**DOMAIN**:Cloud Computing

**DURATION**:16 Weeks

**MENTOR**:NEELA SANTHOSH

# DISCRIPTION OF TASK LIKE HOW YOU PERFORMED AND WHAT YOU HAVE DONE AND PASTE PICTURES OF OUTPUT 

**DISCRIPTION**:Internship Project Report: Cloud Monitoring and Alerts

1. Project Overview  
This project aimed to create a solid monitoring system for a cloud-based application infrastructure. Monitoring is essential for maintaining high availability, tracking resource use, and getting timely alerts for any system issues before they affect end-users. We chose Amazon Web Services (AWS) as the cloud provider and used AWS CloudWatch as the main tool to create custom dashboards and set up automated alerts in real-time.

2. System Deliverables Summary  
We successfully completed the project with two main deliverables:  
- Custom CloudWatch Dashboard: This dashboard, called LearnwithparthDashboard, offers clear visuals for infrastructure resources.  
- Configured CloudWatch Alarm: We developed an alarm named Alert CPU. Its purpose is to monitor system issues actively and notify us of critical resource states.

3. Step-by-Step Implementation Description  
Step 1: Infrastructure Identification  
We identified an AWS EC2 instance running the application as the cloud-based resource to monitor closely. We started standard metrics streams to continuously send data to the CloudWatch management console.

Step 2: Custom Dashboard Creation (LearnwithparthDashboard)  
We created a centralized operational dashboard to gather key performance indicators (KPIs) into one view. We configured three important widgets:  
- CPU Utilization Widget: 
  - Type: Line Graph  
  - Metric: CPUUtilization (in percentages)  
  - Observation: This graph displays a baseline usage and shows a distinct peak reaching about 20.83% on February 27, indicating heavy processing load.  
- Network Out Widget:  
  - Type: Line Graph  
  - Metric: NetworkOut (in bytes)  
  - Observation: The graph reflects the CPU peak, showing data transmission hitting around 122.87 KB. This indicates an increase in outgoing network traffic that matches application activity.  
- Objects Count Widget:  
  - Type: Single Value Number Card  
  - Metric: NumberOfObjects (likely tracking custom application metrics or storage objects)  
  - Observation: It shows a steady count of 2, confirming successful integration of metrics for tracking application data.  

Step 3: Alarm Configuration and Alerting (Alert CPU)  
To shift from passive monitoring to active alerting, we set up an automated threshold alarm.  
- Alarm Setup: We created a CloudWatch alarm named Alert CPU linked to the CPUUtilization metric.  
- Threshold Evaluation: The alarm checks data every minute.  
- Current State ("In Alarm"): We confirmed that the alarm triggered and entered the "In Alarm" (Red) state on February 27, 2026, at 22:11:42 (local time).  
- Action Execution: The system is set to automatically send notifications (for example, via AWS SNS to an administrator's email or webhook) when the threshold is crossed.

4. Conclusion  
We completed the task according to the CodTech Internship Task-2 guidelines. The setup allows us to see infrastructure performance in real-time through the LearnwithparthDashboard. It also protects against unexpected downtime with the Alert CPU monitoring rule.

OUTPUT

https://github.com/Parth-007-git/Cloud-monitoring-and-Alerts/issues/1


