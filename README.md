# Reticulum-Ansible

An ansible role for [Reticulum](https://github.com/markqvist/Reticulum) on Debian 12 and supplemental applications:
- [LXMF](https://github.com/markqvist/lxmf) (LXMD)
- [NomadNet](https://github.com/markqvist/NomadNet)

Work in progress:
- [MeshChat](https://github.com/liamcottle/reticulum-meshchat)
- [Sideband](https://github.com/markqvist/Sideband/)

Defaults are provided based on the packaged defaults for RNSD, a selection of public TCP servers enabled and the AutoInterface enabled.

Additonal roles like LXMF propagation and hosting content with NomadNet can be enabled as required.

Requires Ansible Community version 10.2.0 or greater


To-do:
- Add all additional/remaining Interface configuration settings per [Configuring Interfaces](https://reticulum.network/manual/interfaces.html#)
- Add Meshchat (find a nice way to build/cross compile for low powered platforms/VM's on the ansible server-side prior to install)
- Allow static selection of package version in group/host vars to allow pinning to a version other than "latest"
- Improve documentation in repo and provide more examples/explanation