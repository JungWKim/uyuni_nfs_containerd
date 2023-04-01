# xiilab_nfs
---------------
## how to add worker nodes
### 1. run setup.sh up to specific lines
### 2. In master node, edit $HOME/kubespray/inventory/host.yaml.
### 3. copy master's administrator's public key to worker node
### 4. add worker node into k8s using ansible command
### 5. In worker node, copy config.toml to /etc/containerd/config
### 6. In uyuni dashboard, add worker node.
