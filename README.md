# Kubernates-Zero-to-Hero

# Kubernetes Course – Subtopics Breakdown

---

## 1. **Kubernetes Fundamentals & Architecture**
- What is Kubernetes?
- Kubernetes vs. Docker/VMs
- Cluster architecture: master & worker nodes
- Kubernetes components: API Server, etcd, Controller Manager, Scheduler
- Node components: kubelet, kube-proxy, Container Runtime
- Control plane vs. data plane
- Cluster setup: minikube, kubeadm, managed services
- kubectl basics and authentication

## 2. **Core Resources (Pods, Deployments, etc.)**
- Pod definition and lifecycle
- Multi-container pods (sidecars, ambassadors)
- ReplicaSet and scaling
- Deployments: rolling updates, rollbacks
- StatefulSet: persistent identity, stable storage
- DaemonSet: running pods on all nodes
- Job and CronJob: batch and scheduled tasks
- Namespaces and resource isolation
- Labels, selectors, and annotations

## 3. **Services & Networking**
- Service concept: abstraction and discovery
- Service types: ClusterIP, NodePort, LoadBalancer, ExternalName
- Endpoints and selectors
- DNS integration
- Headless services
- Ingress controllers and resources
- Service mesh basics
- Network policies: traffic control

## 4. **Storage & Persistence**
- Volume types: emptyDir, hostPath, configMap, secret, persistentVolumeClaim, projected
- Persistent Volume (PV) and Persistent Volume Claim (PVC)
- StorageClasses for dynamic provisioning
- Mounting volumes in pods
- Data backup and restore
- StatefulSet and persistent storage

## 5. **Config Management**
- ConfigMaps: storing non-sensitive config
- Secrets: managing sensitive data
- Environment variables in pods
- Mounting configs and secrets as files
- Updating config and secret resources dynamically

## 6. **Security & RBAC**
- Kubernetes authentication and authorization
- RBAC: roles, role bindings, cluster roles
- Service accounts and pod identity
- Network policies for isolation
- Pod security policies (deprecated), alternatives
- Secrets encryption at rest
- Image security and scanning

## 7. **Resource Management & Autoscaling**
- Resource requests and limits (CPU, memory)
- Quality of Service (QoS) classes
- Horizontal Pod Autoscaler (HPA)
- Vertical Pod Autoscaler (VPA)
- Cluster Autoscaler
- Resource quotas and limits per namespace

## 8. **Scheduling & Affinity**
- Scheduler overview
- Node selectors
- Taints and tolerations
- Pod affinity and anti-affinity
- Custom scheduling
- Preemption and priority classes

## 9. **Monitoring & Logging**
- Metrics server basics
- Prometheus and Grafana setup
- Logging: EFK stack, Loki
- Application and cluster monitoring
- Alerting integrations
- Pod and node level logs

## 10. **Health Checks & Lifecycle**
- Liveness, readiness, startup probes
- Pod lifecycle hooks (preStop, postStart)
- Container lifecycle states
- Graceful shutdown and termination policies

## 11. **Upgrades & Maintenance**
- Upgrade strategies (cluster and node)
- Backing up etcd
- Disaster recovery steps
- Maintenance windows and draining nodes
- Rolling upgrades and rollbacks
- Monitoring cluster health during upgrades

## 12. **Advanced Networking (CNI, Service Mesh)**
- CNI plugins: Calico, Flannel, Cilium
- Pod-to-pod networking
- Multi-network setups
- Service mesh: Istio, Linkerd introduction
- Traffic management and observability
- Network policy enforcement

## 13. **Extending Kubernetes (CRDs, Operators)**
- Custom Resource Definitions (CRDs)
- Writing and deploying CRDs
- Kubernetes controllers: custom automation
- Operators: concept and design
- Using existing operators (database, cache, etc.)
- Admission controllers

## 14. **CI/CD & GitOps**
- Kubernetes in CI/CD pipelines
- Automated builds and deployments
- GitOps principles
- Tools: ArgoCD, Flux setup
- Continuous delivery workflows
- Rollbacks and version control

## 15. **Cloud & Hybrid Deployments**
- Managed Kubernetes: GKE, EKS, AKS
- On-premises clusters: kubeadm, k3s, minikube
- Hybrid and multi-cloud clusters
- Federation and cross-cluster management
- Cloud integrations: storage, networking, identity

## 16. **Best Practices & Real-world Projects**
- Namespace organization
- Secure image management
- Resource optimization and cleanup
- Secret management strategies
- Building and deploying a real-world app
- Monitoring, logging, and alerting setup
- Disaster recovery planning
- Cluster scaling and high availability


<img width="940" height="1306" alt="image" src="https://github.com/user-attachments/assets/2885fd92-3335-4d06-a05b-e90d9652bc3a" />

---
