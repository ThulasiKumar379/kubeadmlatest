# Kubeadm install on 10mins
step1:-
apt-get update
step2:-
clone the repo
step3:-
chomd 700 *
step4:-
sh container.sh
sh kubetools.sh
step5:-
sudo kubeadm init
step6:- if anyissue your facing use below command
sudo kubeadm reset
step7:-
run 3 commands for getting kubeadm
step8:-
install the calico network
step9:-
kubectl apply -f calico.yaml
step10:-
kubectl get nodes
step11:-
use the join command in worker nodes
