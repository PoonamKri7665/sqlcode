# k8s yamlfiles
### k8s commands 
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
  350  sudo apt install curl
  351  curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
  352  sudo install minikube-linux-amd64 /usr/local/bin/minikube
  353  minikube start
  354  minikube delete --all
  355  sudo install minikube-linux-amd64 /usr/local/bin/minikube
  356  minikube status
  357  minikube start
  358  docker --version
  361  minikube version
  362  minikube start
  363  sudo apt update
  371  apt-get install curl wget apt-transport-https -y
  372  sudo apt-get install curl wget apt-transport-https -y
  373  sudo apt-get install virtualbox virtualbox-ext-pack
  374  wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
  375  cp minikube-linux-amd64 /usr/local/bin/minikube
  376  sudo cp minikube-linux-amd64 /usr/local/bin/minikube
  377  chmod 755 /usr/local/bin/minikube
  378  sudo chmod 755 /usr/local/bin/minikube
  379  minikube version
  380  sudo snap install kubectl --classic
  381  minikube start
  384  minikube version
  385  kubectl version --output=yaml
  400  curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
  401  sudo install minikube-linux-amd64 /usr/local/bin/minikube
       minikube start --driver=docker
  407  minikube delete
  408  minikube start --driver=docker
  409  sudo minikube start --driver=docker
  410  sudo usermod -aG docker jaya && newgrp docker
  411  kubectl apply -f pod.yml
       kubectl get pod -w
  414  kubectl get pod
  415  kubectl get pod -o wide
  416  kubectl describe pod pkpod
  kubectl delete pod pkpod
  449  kubectl get pod
  450  kubectl apply -f pod1.yml
  451  kubectl apply -f pod1.yaml
  452  kubectl delete -f pod1.yaml
  453  kubectl run hello --image nginx --port 80
  454  kubectl get pod
  455  kubectl run hello --image nginx --port 80 --dry-run=client
  456  kubectl get pod
  457  kubectl run hello --image nginx --port 80 --dry-run=client -o=yaml
  458  kubectl run hello --image nginx --port 80 --dry-run=client -o=yaml >podtest.yaml
  459  kubectl apply -f podtest.yaml
  460  kubectl get pod
  461  kubectl exec -it hello --bash
  462  kubectl exec -it hello -- bash
  463  kubectl get pod
  464  kubectl get pod -A
  465  kubectl get namespace
  466  kubectl get ns
  467  kubectl create  ns poonam
  468  kubectl get ns
  469  kubectl get pod --namespace kube-system
  470  kubectl apply -f podtest.yaml
  471  kubectl delete helloc
  472  kubectl delete pod helloc
  473  kubectl delete pod hello
  474  kubectl get pod