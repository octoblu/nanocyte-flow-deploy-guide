# Nanocyte Flow Deploy Guide


#### Meshblu Authentication
  Make sure you have your user UUID and Token set as MeshbluAuth in the header

#### Deployment UUID
  Optional UUID used to distinguish unique deployments

---
### Starting A Flow
```
POST /flows/{flowId}/instances
```
---
### Stopping A Flow
```
DEL /flows/{flowId}/instances
```
---
