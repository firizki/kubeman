# Kubeman
Kubeman stand for Kubectl Manager. Kubeman will execute every command like `kubectl` do, but Kubeman will change `kubectl` binary if it's detect different version between client and server.

## Requirement
- You must already install `kubectl` binary
- Make sure you have `~/.kube/` directory

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
