
## [calico](https://www.projectcalico.org/)

- Calico is an open source networking and network security solution for containers, 
  virtual machines, and native host-based workloads.


- [quick start](https://docs.projectcalico.org/getting-started/kubernetes/quickstart)


- Self-managed on-premises
  - Install Calico for on-premises deployments to provide networking and network policy, 
    in either overlay or non-overlay networking modes.

- Self-managed public cloud
    - Manage your own Kubernetes clusters in AWS, GCE, or Azure public clouds.

- Self-managed Kubernetes in AWS/GCE/Azure/DigitalOcean
    - Use Calico with a self-managed Kubernetes cluster in public clouds

- Managed public cloud
    - Enable Calico network Policy on EKS, GKE, AKS

- K3s  
    - Get Calico up and running in your K3s cluster
- MicroK8s
- minikube 


- Manage your Kubernetes network policies right alongside the more powerful Calico network policies.

    - Get started with Kubernetes network policy
            - Learn Kubernetes policy syntax, rules, and features for controlling network traffic.

    - Kubernetes policy, demo
         - An interactive demo that visually shows how applying Kubernetes policy allows and denies connections.

    - Kubernetes policy, basic tutorial
            - Learn how to use basic Kubernetes network policy to securely restrict traffic to/from pods.

    - Kubernetes policy, advanced tutorial
            - Learn how to create more advanced Kubernetes network policies
             (namespace, allow and deny all ingress and egress).





- Security 
    - Policy Rules
    - Policy for hosts
    - Policy for Kubernetes services
    - 

    - Adopt a zero trust network model for security
    - Policy rules
        - Control traffic to/from endpoints using Calico network policy rules.
            -  Basic rules
                - Define network connectivity for Calico endpoints using policy rules and label selectors.

            - Namespace rules
                - Use namespaces and namespace selectors in Calico network policy to group or separate resources. 
                  Use network policies to allow or deny traffic to/from pods that belong to specific namespaces.

            - Service accounts rules
                - Use Kubernetes service accounts in policies to validate cryptographic identities and/or 
                  manage RBAC   controlled high-priority rules across teams.

            - External IPs or networks rules
                - Limit egress and ingress traffic using IP address either directly within Calico network policy or 
                  managed as Calico network sets.

            - ICMP/ping rules
                 - Control where ICMP/ping is used by creating a Calico network policy to allow and deny ICMP/ping   messages for workloads and host endpoints.

    
    Policy for hosts
Use the same Calico network policy for workloads to restrict traffic between hosts and the outside world.

Protect hosts
Calico network policy not only protects workloads, but also hosts. Create a Calico network policies to restrict traffic to/from hosts.

Protect Kubernetes nodes
Protect Kubernetes nodes with host endpoints managed by Calico.

Protect host tutorial
Learn how to secure incoming traffic from outside the cluster using Calico host endpoints with network policy, including allowing controlled access to specific Kubernetes services.

Apply policy to host forwarded traffic
Apply Calico network policy to traffic being forward by hosts acting as routers or NAT gateways.




Policy for Kubernetes services :

    - Apply Calico policy to Kubernetes node ports, and to services that are exposed externally as cluster IPs.

    - Apply policy to Kubernetes node ports
        - Restrict access to Kubernetes node ports using Calico global network policy. Follow the steps to secure the host, the node ports, and the cluster.

    - Apply policy to services exposed externally as cluster IPs
        - Expose Kuberenetes service cluster IPs over BGP using Calico, and restrict who can access them using Calico network policy.



