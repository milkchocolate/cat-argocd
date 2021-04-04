# Argo CD Deployment
1. Apply ```namespace.yaml```
2. Set argocd-server to insecure for local use
3. Disable sidecar injection for argocd-repo-server
4. Apply install.yaml with specific namespace ```kubectl apply -n argocd -f install.yaml```
5. Apply the rest of the things