Before starting to deploy K8S  
1.We should first set the `hostname` and `hosts` of the nodes  
2.set root ssh login `echo PermitRootLogin Yes | sudo tee -a /etc/ssh/sshd_config`  
3.install openssh-server `sudo apt-get install openssh-server`  
  
 --------------------------------   
  
ssh setup  
`ssh-key`
>Let ssh login without password  
  
 --------------------------------   
  
Kubernetes-deploy  
`cri-o > k8s-master > k8s-worker`
>cri-o : install CRI cri-o  
>k8s-master : create K8S master  
>k8s-worker : create K8S worker  
>podman : install podman  
>check : check version and status   
>reboot : reboot nodes  
 --------------------------------   
