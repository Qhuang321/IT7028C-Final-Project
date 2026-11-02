# IT 7028C Final Project -Phase I Setup

## Virtual Machines
- VM1:dev-vm - Development workstation
- VM2: k8s-vm - Kubernetes deployment server
- VM1 and VM2 conectivity verified with successful ping tests.
- VM addresses are currently assigned using DHCP.

## GitHub
-Repository: Qhuang321/IT7028C-Final-Project
- Branches: main, develop, feature/qhuang-setup
- SSH authentication configured on VM1.

## Docker
- Docker installed and tested on both VMs.
- hello-world container executed successfully.

## Kubernetes
- Kubectl installed on both VMs.
- Kind and Helm installed.
- Kind cluster created on VM2: cloud-admi
- Kubernetes control-plane node verified Ready.
-CoreDNS and Kubernetes control plane verified.

## Remaining Work
- Confirm static IP requiremens with the instructor.
- Finish team collaboration and individual feature branches.
- Implement CI/CD in Phase II

