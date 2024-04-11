# Configure demo app in ArgoCD on k3d

    cd argo-artifacts
    kubectl apply -f . -n dev

Deploys the app in namespace dev.

This example is a clone of [GitOps on a Laptop with K3D and ArgoCD](https://www.sokube.io/en/blog/gitops-on-a-laptop-with-k3d-and-argocd-en).

The repo is forked from [argocd-rocks](https://github.com/sokube/argocd-rocks).