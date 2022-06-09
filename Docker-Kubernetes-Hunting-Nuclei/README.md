# Kube-Hunt-Nuclei



    nuclei -u https://IP -t . -vv
 
    nuclei -u https://IP -t . -vv
 
    nuclei -u https://IP -t . -vv
 

Specific Example : 
  
    nuclei -t kube-api-scan.yaml -target https://<ip>:6443

    nuclei -t kubelet-scan.yaml -target http://<ip>:10250

    nuclei -t etcd-scan.yaml -target http://<ip>:2379
    
    
The following ports might be open in a Kubernetes cluster


    nmap IP -sV

    nmap IP -sV

    nmap IP -sV -oA k8s-pt

    nmap IP -sV -oA k8s-pt

    nmap IP -p- -sV -oA k8s-pt-full-scan

    nmap -n -T4 -p 443,2379,2378,6666,4194,6443,8443,8080,10250,10255,10256,9099,6782-6784,30000-32767,44134 194.5.207.20
