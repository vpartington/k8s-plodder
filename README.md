# container-tools
Docker image with tools for debugging and troubleshooting:
* curl
* dig
* host
* netcat
* nslookup
* ping
* [skopeo](https://github.com/containers/skopeo) 
* telnet
* traceroute
* wget

# Start with
```
kubectl run container-tools-$$ --image=vpartington/container-tools --interactive --tty --rm bash
```

# Or create an alias:
```
alias k8sct='kubectl run container-tools-$$ --image=vpartington/container-tools --interactive --tty --rm bash'
```
