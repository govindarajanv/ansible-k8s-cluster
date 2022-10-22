ansible-playbook -i hosts ~/kube-cluster/initial.yml --ask-become-pass


https://www.digitalocean.com/community/tutorials/how-to-create-a-kubernetes-cluster-using-kubeadm-on-ubuntu-20-04
ssh-keygen
ssh-copy-id username@remote_host



ansible-playbook -i hosts ~/kube-cluster/control-plane.yml --ask-become-pass
