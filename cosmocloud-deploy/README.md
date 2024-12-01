# Cosmocloud Deploy
This Helm chart deploys a full-stack application consisting of:
- **Backend**: shreybatra/sample-backend
- **Frontend**: shreybatra/sample-frontend
- **Redis**: Redis database

## Deployment Instructions
1. Install the chart:
   ```bash
   helm install testapp cosmocloud-deploy --atomic --timeout 30s
## To verfiy the deployment below is the command
kubectl get all

