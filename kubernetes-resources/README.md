# Argo CD Deployment
1. Set argocd-server to insecure for local use
2. Disable sidecar injection for argocd-repo-server
3. Apply install.yaml with specific namespace ```kubectl apply -n argocd -f install.yaml```
4. Apply the rest of the things