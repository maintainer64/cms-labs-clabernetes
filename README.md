[![Discord](https://img.shields.io/discord/860500297297821756?style=flat-square&label=discord&logo=discord&color=00c9ff&labelColor=bec8d2)](https://discord.gg/vAyddtaEV9)
[![Go Report](https://img.shields.io/badge/go%20report-A%2B-blue?style=flat-square&color=00c9ff&labelColor=bec8d2)](https://goreportcard.com/report/github.com/srl-labs/clabernetes)

# CMS Labs Clabernetes

This repository is the CMS Labs fork of upstream
[`srl-labs/clabernetes`](https://github.com/srl-labs/clabernetes). The `cms`
branch adds opt-in `ttyd`/tmux terminals (`ttyd-shell` per topology node) and
publishes the controller, launcher and OCI Helm chart for the CMS Labs stack.
The Go module and Kubernetes API names intentionally remain upstream-compatible.

## Upstream project

<p>
  <img src="https://gitlab.com/rdodin/pics/-/wikis/uploads/b5d611838fcb9c588b6311bccf11b954/c9s_logo1-upscale2x-white-tag+font-min__1_.png" width="200" align="left" alt="clabernetes"/>
  Love containerlab? Want containerlab, just distributed in a kubernetes cluster? Enter
  clabernetes -- containerlab + kubernetes. clabernetes is a kubernetes controller that deploys valid
  containerlab topologies into a kubernetes cluster.

  See [clabernetes docs](https://containerlab.dev/manual/clabernetes) for reference.
</p>
