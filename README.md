Use  git clone https://github.com/ragatgen/kubectl-aks-debug-node.git and then

cd to the Directory named as the Repo kubectl-aks-debug-node



sudo mv kubectl-aks-debug-node /usr/local/bin/
sudo chmod +x /usr/local/bin/kubectl-aks-debug-node

Test
kubectl-aks-debug-node

Verify that it’s listed as a plugin:

randra@Lenovo-WorkRG:/mnt/c/Users/ragatgen$ kubectl plugin list


/usr/local/bin/kubectl-aks-debug-node
/usr/local/bin/kubectl-convert
randra@Lenovo-WorkRG:/mnt/c/Users/ragatgen$ 
