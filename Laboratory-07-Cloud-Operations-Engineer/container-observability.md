# Container Observability Report

## Application Logs Analysis

### 404 Error Log Line
172.17.0.1 - - [07/Oct/2026:02:00:27 +0000] "GET /hidden-admin-page HTTP/1.1" 404 153 "-" "curl/8.5.0" "-"


### Why Application Logs are Vital for Troubleshooting

Application logs act like a security camera for your web server. They record every request that reaches the application, including the timestamp, IP address, requested path, and HTTP status code. When something goes wrong, these logs allow engineers to quickly identify whether the issue is a missing page (404), a server error (500), or unauthorized access, making it much faster to diagnose and fix problems.

---

## Real-Time Container Metrics

### client-website Resource Usage

| Metric          | Value                  |
|-----------------|------------------------|
| **Memory Usage** | 2.734MiB / 1.859GiB   |
| **CPU %**        | 0.00%                  |

### Observation

The Nginx container consumed very little memory (only 2.734MiB) and almost zero CPU while handling the test requests. This indicates that the container is running efficiently and has enough headroom to handle a larger traffic surge.
