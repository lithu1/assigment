# 1
## Explain the difference between metrics, logs, and traces.

**Metrics:**  
Numerical data collected over time to measure system performance.

**Logs:**  
Timestamped records of events happening inside the system.

**Traces:**  
Records the journey of a single request as it moves through various services.

# 2
## If your Kubernetes pod crashes, how would you debug the issue? (write the commands and reasoning).

1. **Check the status of the pods**  
   **Command:**  
   ```bash
   kubectl get pods

2. **next check with describing the pod to know detailed information where the error is  **
   **Command:**  
   kubectl describe pod <pod-name>


3. **next I also check with the logs of the pods to see what is the error  **
**Command:**  
kubectl logs <pod-name>
4. if the above also fails I will directly login into the pod and run the command manually  
**Command:**  
kubectl exec -it <pod-name> -- /bin/bash




###  3
## What tools would you suggest for monitoring in AWS EKS and why? (Prometheus, CloudWatch, Grafana, ELK stack, etc.)

I would use **CloudWatch** as the monitoring tool because it is easy to integrate with AWS services.  
For visualization, I would use **Grafana**.

