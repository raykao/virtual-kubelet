# NodeJS Web Provider for Virtual Kubelet

This repository is an example web provider for Virtual Kubelet written in NodeJS as a reference guide.

## Requirements

For VK to simply register your node with your Kubernetes cluster (i.e. show up when running ```kubectl get nodes```), you will need to implement (at minimum):
- [handlers/capacity.js](src/handlers/capacity.js)
- [handlers/nodeConditions.js](src/handlers/nodeConditions.js)
- [handlers/nodeAddresses.js](src/handlers/nodeAddresses.js)