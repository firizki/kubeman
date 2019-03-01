# Kubeman
Kubeman stand for Kubectl Manager. Kubeman will execute every command like `kubectl` do, but Kubeman will change `kubectl` binary if it's detect different version between client and server.

## Requirement
- You must already install `kubectl` binary that possible to change config context
- Make sure you have `~/.kube/` directory
- Currently it's only support Linux base, you can change this by change the link with [Install and Set Up kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
  

## Installation
1. Set kubeman as execute file
```
chmod +x kubeman
```
2. Copy kubeman to your bin folder
```
cp kubeman /usr/local/bin/kubeman
```
## How To Use
Everytime you change your context, Kubeman will check client & server version.
```
kubeman config use-context <your-context>
```
