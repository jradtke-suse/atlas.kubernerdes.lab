# README

Atlas is my PXE host (http/s, tftp, dns, dhcp).
It is a VM running on [Kubernerd](https://github.com/jradtke-suse/kubernerd.kubernerdes.lab)

This host relies on SLES 15 to provide a PXE boot environment, which is then configured to deploy SUSE Virtualization (aka Harvester).

This repo is primarily focused on a setup to accommodate 3 x Intel NUCs.  The NUC has some unique characteritstics and dependencies (such as requiring tftp to start the network install process).

- Install SLES 15
- Configure OS (storage, firewall)
- Install and configure additional software packages
- monitor during client installs

