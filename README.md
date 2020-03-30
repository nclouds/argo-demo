# argo-demo


kubectl create namespace argo-cd-demo

argocd app create argo-cd-demo --repo https://github.com/nclouds/argo-demo.git --path . --dest-server https://kubernetes.default.svc --dest-namespace argo-cd-demo --sync-policy automated
