# Remote production environment workspace

Be careful when using scripts in this workspace, as you risk breaking production instances!

## Introduction

This workspace allows you to interact with remote production environment instances
(applications, databases, etc.) within the [GitOps](https://www.gitops.tech/) paradigm.

This workspace is designed, among other things, to store the configuration of production instances.  
It includes scripts for deploying this configuration to remote instances and analysing
the differences between the theoretical or desired configuration and that actually deployed.  
With Git, these configurations are versioned, making it possible to track changes made over
time on these instances.  
Furthermore, this paradigm allows modifications to be proposed in the form of Pull Requests,
simplifying collaborative work.

## Workspace configuration

...
