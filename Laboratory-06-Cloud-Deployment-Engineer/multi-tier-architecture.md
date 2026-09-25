# Multi-Tier Architecture

## Two-Tier Architecture

A two-tier architecture separates an application into two main layers: the Web/Application Tier and the Database Tier.

### The Web/Application Tier
This tier is responsible for serving the user interface and handling HTTP requests. In our deployment, the Nextcloud container acts as the web/application tier. It receives requests from users through a web browser, processes them, and displays the private cloud interface.

### The Database Tier
This tier stores persistent data such as user accounts, file metadata, and configurations. In this lab, the MariaDB container serves as the database tier. It keeps all important information safe and available even when the web application restarts.

### Why separate them?
It is better to run the web server and the database in two separate containers because it improves security, scalability, and maintainability. If one container fails, the other can still continue working. It also allows each component to be updated or scaled independently without affecting the entire system.
