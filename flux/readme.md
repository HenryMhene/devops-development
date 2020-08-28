kubectl create ns flux

export GHUSER="henrymhene"
fluxctl install \
--git-user=${GHUSER} \
--git-email=${GHUSER}@users.noreply.github.com \
--git-url=git@github.com:${GHUSER}/devops-development.git \
--git-path=flux \
--namespace=flux | kubectl apply -f -

kubectl -n flux rollout status deployment/flux

fluxctl identity --k8s-fwd-ns flux