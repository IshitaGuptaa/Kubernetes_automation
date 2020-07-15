Wordpress setup using Automation

The project makes use of kubernetes to launvh wordpress and ensures high availability and disaster recovery.

Use the Kustomisation setup, one command and entire setup will be up and ready to use.

Command for Kustomization- 

kubectl apply -f .

Conditions:
-  Kubectl and minikube or any minikube cluster, should be there.
-  For systems other than minikube host, we need setup configuration, that file too is present in the projet under the name of config. 
paste the config file in the /root/.kube/ folder
 command: cp config.yml /root/.kube/config




