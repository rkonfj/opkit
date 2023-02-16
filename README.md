# A operations tool kit

### 1. hooklay
WebHook relay middleware. A tools forward web hook to other web hook endpoint with json render

[README.md](cmd/hooklay/README.md)

### 2. kdt
Kubernetes based Deploy Tools.

```
# kdt --help
kubernetes based deployments tools

Usage:
  kdt [command]

Available Commands:
  completion  Generate the autocompletion script for the specified shell
  diff        Show different deployments from A to B
  envs        Show all environments
  help        Help about any command
  image       Show environment's images
  jstack      Dump target environment jvm deployment's stack
  jvmgc       Get target environment jvm deployment's gc log
  push        Push different deployments from A to B
  restart     Restart target deployments

Flags:
  -h, --help   help for kdt

Use "kdt [command] --help" for more information about a command.
```
[README.md](cmd/kdt/README.md)
