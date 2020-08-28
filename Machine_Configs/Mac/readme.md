# Getting Started

## CLI Installations

```
#Install Docker
https://hub.docker.com/editions/community/docker-ce-desktop-mac/
```

```
#Install AWS cli
https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-mac.html
```

```
#Install Terraform
https://learn.hashicorp.com/tutorials/terraform/install-cli?in=terraform/aws-get-started

brew install terraform
brew install wget
```

```
#Install Kubectl
Kubectl autocomplete 
BASH
source <(kubectl completion bash) # setup autocomplete in bash into the current shell, bash-completion package should be installed first.
echo "source <(kubectl completion bash)" >> ~/.bashrc # add autocomplete permanently to your bash shell.
You can also use a shorthand alias for kubectl that also works with completion:

alias k=kubectl
complete -F __start_kubectl k
```

```
#Install fluxctl
brew install fluxctl
```