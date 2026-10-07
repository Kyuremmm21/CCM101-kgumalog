# Laboratory 07 – Cloud Operations Engineer

## Mission Overview

In this laboratory activity, I stepped into the role of a Cloud Operations Engineer (Site Reliability Engineer) at CloudNova Technologies. The goal was to establish a performance baseline for a Linux server, deploy a containerized Nginx web application, generate artificial web traffic, and use observability tools (metrics and logs) to prove that the infrastructure is healthy and ready for a large traffic surge.

Deploying an application is only the first step — keeping it running smoothly requires continuous monitoring of host resources, container metrics, and application logs.

## Objectives

By completing this mission, I was able to:

- Utilize native Linux command-line tools to monitor host CPU, Memory, and Disk capacity
- Deploy a web container and track its real-time performance using Docker metrics
- Generate web traffic and extract application access logs for analysis
- Translate raw performance data into a readable technical report using Markdown
- Continue expanding my professional GitHub Cloud Computing Portfolio

## Monitoring Commands Executed

### Host System Baseline
```bash
free -h                  # Check memory (RAM) usage
df -h                    # Check available disk storage
top                      # View active processes and CPU load
