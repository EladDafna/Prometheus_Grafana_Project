## Grafana Dashboard for Kubernetes Monitoring

In this project, I developed a comprehensive Grafana dashboard to monitor the health and performance of a Kubernetes cluster. Leveraging Prometheus as the data source, the dashboard provides real-time insights into various critical metrics across different levels of the cluster.

### Project Overview:

- **Node Level Monitoring**: Track the number of running pods on each node, CPU usage by cores, and overall CPU percentage.
- **Namespace Level Monitoring**: Monitor pod restarts, CPU usage, the number of running pods, deployments, network traffic (receive and transmit), and memory usage within each namespace.
- **Pod Level Monitoring**: Assess network traffic, disk I/O read and write, CPU usage percentage, pod age, average memory usage, and CPU consumption for individual pods.
- **Container Level Monitoring**: Keep an eye on CPU and memory usage at the container level.

The data is sourced from Prometheus and visualized through Grafana, which enables dynamic querying and detailed monitoring. By incorporating variables for node, namespace, pod, and container, the dashboard ensures flexible and granular analysis of cluster metrics.

---

**My Custom Dashboard:**

### By Node:
![Node Level Metrics](https://github.com/user-attachments/assets/4be94b86-26d5-4619-8e23-2d6d6ad31ffd)

*This screenshot displays the monitoring of various metrics at the node level, including the number of running pods, CPU usage by cores, and overall CPU percentage.*

### By Namespace:
![Namespace Level Metrics](https://github.com/user-attachments/assets/b27fb8c2-3eac-46b7-98b4-dc7e83e1adae)

*This image illustrates the metrics tracked at the namespace level, such as pod restarts, CPU usage, number of running pods, deployments, network traffic (receive and transmit), and memory usage.*

### By Pod:
![Pod Level Metrics](https://github.com/user-attachments/assets/69bbc007-cb6f-4e7f-b191-fab7a3abcf0e)

*Here, you can see the detailed monitoring of individual pods, including network traffic, disk I/O read and write, CPU usage percentage, pod age, average memory usage, and CPU consumption.*

### By Container:
![Container Level Metrics](https://github.com/user-attachments/assets/5ab66e38-c2b1-4d68-8928-f28202674dc0)

*This screenshot highlights the monitoring of CPU and memory usage at the container level.*

