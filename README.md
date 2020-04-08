# apm-vpn-optimisation
F5 APM VPN Conifguration Optimisation

This consists of four files:
- apm-vpn-optimisation_icall.tmpl which is an iApp which creates an iCall to make changes to connectivity and network access profiles to reduce CPU usage
- apm-vpn-optimise - a shell script which prints out the current status and commands to make recommended changes
- o365_iapp.tmpl - an iApp which creates an iCall to run the O365 Optimisation script created by Regan Anderson at https://github.com/f5regan/o365-apm-split-tunnel
- apm_dtls_iapp.tmpl which is an iApp to clone an existing virtual server and create a UDP virtual server as well as modify the network access profile.
