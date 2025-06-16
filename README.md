✅ Automated Kubernetes Cluster Setup using kubeadm and Ansible
This guide describes how to automate the setup of a Kubernetes cluster (control plane and worker nodes) using Ansible and kubeadm.

1. Prerequisites
Ensure the following:

- You have SSH access to all target nodes (control plane and workers)

- All nodes run a compatible Linux OS (e.g., Ubuntu 20.04 or CentOS 7/8)

- Internet access (or a mirrored registry or proxy) is available on all nodes

- A dedicated Ansible control node (can be your local machine or a remote server)

2. Install Python and Ansible on the Ansible Control Node
On the Ansible control node:
sudo apt update && sudo apt install -y python3 python3-pip
pip3 install ansible

3. Create the controlplane and workernode yaml file
   
4. Create the hosts.ini file
 
5. Run the script with the below command
- e.g ansible-playbook -i hosts.ini controlplane.yaml
