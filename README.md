# k3s


stripped down version of official k3s ansible for my own needs

to check latest k3s version go to: https://github.com/k3s-io/k3s/releases
and update inventory.yml

check with 

$kubectl get nodes 

on master node


$ansible-playbook site.yml

$ansible-playbook upgrade.yml
