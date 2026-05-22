# Windows Authentication Log Analysis

## Overview
This project demonstrates basic security monitoring and log analysis using system event logs.

## Objective
To identify and analyze successful and failed login attempts using system security logs.

## Tools Used
- Windows Event Viewer

## Incident Scenario
A user generated multiple failed login attempts followed by a successful login to simulate suspicious authentication behavior. Security logs were analyzed to identify the events and review authentication details.

## What I Did
- Accessed and navigated system security logs
- Identified login-related events (Event ID 4624 and 4625)
- Simulated failed login attempts
- Analyzed event details such as timestamps, user accounts, and logon types

## Security Findings
- Identified multiple failed login attempts (Event ID 4625)
- Confirmed successful authentication events (Event ID 4624)
- Observed how Windows records authentication activity in security logs
- Demonstrated basic log analysis and event investigation workflow

## Screenshots
![Security Logs](security-log-overview.png)

![Failed Login Attempt](failed-login-event.png)

![Successful Login](successful-login-event.png)

![Event Details](event-details-analysis.png)

## Skills Demonstrated
- Log analysis
- Security monitoring
- Threat detection basics
- Troubleshooting

## Key Takeaways
This project helped me understand how security events are logged and how analysts can detect suspicious activity through log monitoring.
