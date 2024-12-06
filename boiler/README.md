# devlocal

`devlocal` is a tool to enable you to get quick started with all the necessary systems pre-installed. 

# Batteries Included

`setup.config` is the go to place to configure the relevant options for your setup.


The following are crucial to future-proof your setup. 
You setup a SSH keys(currently only supporting GitHub and Gitlab Cloud), you can modify the taskfile to support other forms of git repos as well. 

Then you have a System App of Apps and a Application App for Apps. The former serve as an extension to your ecosystem install tools you need, for instance, Tekton. 

Application App of Apps is the place where you onboard custom apps that you developed. 

```
...
### SSH KEY to access GIT REPOS
PATH_TO_SSH_KEY=~/.ssh/id_ed25519.argo

### SYSTEM App of apps
# This is where you add ARGOCD's to install dependencies that you need
# example, Kestra or Jenkins for CI/CD support, ISTIO, etc 
SYSTEM_APP_OF_APPS=""

### Application App of apps
# This is where you onboard Application to you need
# example, Kestra or Jenkins for CI/CD support 
APPLICATION_APP_OF_APPS=""
...
```

# Design and Behaviors for different system

It is recommend to use this on a linux compatible machine. 
However, if you are using Window's WSL, then there are some work around which you might refer to [Notes](Notes.md)
