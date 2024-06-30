## Prerequisites
**Kubernetes Cluster:** Ensure you have access to a running Kubernetes cluster.  
**Helm:** Helm should be installed and configured to interact with your Kubernetes cluster.   
## Configuration Overview
The provided configuration values set up GitLab Runner with the following key settings:

**Image Configuration:** Specifies the GitLab Runner image from the GitLab registry.   
**Concurrency:** Sets the number of concurrent runners to 10.
RBAC: Role-Based Access Control (RBAC) is enabled.    
**Namespace:** The GitLab Runner is deployed in the gitlab-runner namespace.   
**Runner Registration:** The runner is registered to the specified GitLab instance using the provided registration token.  
**Node Selector:** The runner pods are scheduled on nodes with the label gitlab=true.
