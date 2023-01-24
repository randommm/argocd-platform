<code>kubectl create namespace argocd; kubectl apply -f https://raw.githubusercontent.com/argoproj/argo-cd/master/manifests/install.yaml -n argocd</code>

<code>kubectl apply -f https://raw.githubusercontent.com/randommm/argocd-platform/master/projects.yaml</code>

<code>kubectl apply -f https://raw.githubusercontent.com/randommm/argocd-platform/master/apps.yaml</code>

This repo is based on https://github.com/vfarcic/argocd-platform (which is also Apache 2 licensed).
