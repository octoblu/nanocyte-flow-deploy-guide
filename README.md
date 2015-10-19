# Nanocyte Flow Deploy Guide

## Authentication
  All requests require authentication with Meshblu UUID & Token. Make sure you have your user UUID and Token set as MeshbluAuth in the header.


#### Deployment UUID (optional)
  Optional UUID used to distinguish unique deployments


## Making Your Request

### Deploying A Flow
```
POST /flows/{flowId}/instances/
```

### Stopping A Flow
```
DEL /flows/{flowId}/instances
```
---


You can clone down this repo and follow the instructions to generate scripts to easily deploy a flow, click a trigger, and subscribe to pulses.
```
git clone git@github.com:octoblu/nanocyte-run-production-locally
```
