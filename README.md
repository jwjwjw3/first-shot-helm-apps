# First-Shot-Helm-Apps
This repo contains minimal (almost the simplest) helm chart config YAML files for multiple cloud native applications for people new to K8s or helm. 

This repo is for developers and cloud admins who are playing with cloud native applications using helm for the FIRST time. If you want to install an app listed in this repo, you find the provided helm chart config file from the official documentation is too complicated for you, and you want a minimal configuration just to get your app running so that you can start playing or debugging, then this is the correct repo for you.

The provided YAML files can be used with command `helm install`. The CPU and RAM usages per app should be very small, the app should be up and running in a few minutes as long as your K8s cluster is not terribly crowded. 