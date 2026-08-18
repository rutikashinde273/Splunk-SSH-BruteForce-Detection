# Splunk SSH Brute-Force Attack Detection

## Overview

This project demonstrates SOC monitoring and SSH brute-force attack detection using Splunk Enterprise.

The project analyzes Linux SSH authentication logs to identify failed and successful login attempts, suspicious source IP addresses, targeted usernames, and potential brute-force activity.

## Objectives

- Monitor SSH authentication logs
- Identify failed SSH login attempts
- Monitor successful SSH logins
- Identify suspicious source IP addresses
- Analyze targeted usernames
- Detect potential SSH brute-force attacks
- Visualize security events using a Splunk dashboard

## Tools & Technologies

- Splunk Enterprise
- Splunk Search Processing Language (SPL)
- Linux SSH Authentication Logs
- SIEM
- Security Monitoring
- Log Analysis

 Project Workflow

SSH Authentication Logs  
↓  
Splunk Ingestion  
↓  
SPL Queries  
↓  
Failed Login Analysis  
↓  
Source IP Analysis + Username Analysis  
↓  
Brute-Force Detection  
↓  
Splunk SOC Dashboard  

## Dataset

The project uses SSH authentication logs containing:

- Successful SSH logins
- Failed password attempts
- Invalid user attempts
- Source IP addresses
- Target usernames
- Authentication timestamps

The dataset is available in:

dataset/ssh_auth.log

## SPL Queries

The complete SPL queries used in this project are available in:

queries/ssh_detection_queries.spl
