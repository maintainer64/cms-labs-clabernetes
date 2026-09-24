[![Discord](https://img.shields.io/discord/860500297297821756?style=flat-square&label=discord&logo=discord&color=00c9ff&labelColor=bec8d2)](https://discord.gg/vAyddtaEV9)
[![Go Report](https://img.shields.io/badge/go%20report-A%2B-blue?style=flat-square&color=00c9ff&labelColor=bec8d2)](https://goreportcard.com/report/github.com/srl-labs/clabernetes)

# clabernetes a.k.a c9s

Love containerlab? Want containerlab, just distributed in a kubernetes cluster? Enter
clabernetes -- containerlab + kubernetes. clabernetes is a kubernetes controller that deploys valid
containerlab topologies into a kubernetes cluster.

See [clabernetes docs](https://containerlab.dev/manual/clabernetes) for reference.

## Deploy

Deploying this chart is like deploying any other helm chart! The simplest case looks something like:

```bash
helm upgrade --install clabernetes oci://ghcr.io/maintainer64/cms-labs-clabernetes/clabernetes
```

You can select a specific chart version with `--version`. Published versions are available in the
[CMS Labs package registry](https://github.com/maintainer64/cms-labs-clabernetes/pkgs/container/cms-labs-clabernetes%2Fclabernetes).

## Values

As with most Helm charts, this chart is configurable through its
[default values](https://github.com/maintainer64/cms-labs-clabernetes/blob/cms/charts/clabernetes/values.yaml).
