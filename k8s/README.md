# k8s-samples

### cluster-terminal-pod

Instead of debian, consider using nicolaka/netshoot or busybox or even praqma/network-multitool for cluster testing—they come preinstalled with useful networking/debug tools.

Alternative

kubectl run -it debug --rm --image=debian -- bash