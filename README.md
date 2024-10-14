# DevPod Go Example

[![Open in DevPod!](https://devpod.sh/assets/open-in-devpod.svg)](https://devpod.sh/open#https://github.com/ceghap/go-template)

## Quickstart

Either click on the 'Open in DevPod' link above or start via `devpod up github.com/ceghap/go-template`. This will start a small devcontainer that has all the needed tools to start working on a go server.
It will also serve static files on port 4000 and forward it to your local machine.

After creating your workspace, run `go run main.go` to start the server.

## What's inside?
- VS Code Go extensions


## Git Setup

1. First make this workspace as a safe directory `git config --global --add safe.directory /workspaces/learn-go`
1. Generate ssh key `ssh-keygen -t rsa-sha2-256 -b 2048`
1. Copy the generated keygen `cat ~/.ssh/id_rsa.pub`
1. Paste in your github SSH & GPG Keys in the setting.