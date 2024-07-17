# asdf-argocd-image-updater

[argocd-image-updater](https://argocd-image-updater.readthedocs.io) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```sh
asdf plugin-add argocd-image-updater https://github.com/thatmlopsguy/asdf-argocd-image-updater.git
```

```sh
# Show all installable versions
asdf list all argocd-image-updater

# Install latest version
asdf install argocd-image-updater latest

# Set a version globally
asdf global argocd-image-updater latest

# Set a version locally
asdf local argocd-image-updater latest

# Now argocd commands are available
argocd-image-updater
```

## Use

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install and manage versions of
`argocd-image-updater`.
