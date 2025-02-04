# softether_vps
Ansible scripts for SoftEther VPN install and configure with (or without) L2TP/IPSec and Cloudflared DOH on CentOS-based VPS.

1. softether_redhat.yaml - install and configure SoftEther on 443 port. Usage example: ansible-playbook -i put_your_vps_ip_here, softether_redhat.yaml -u root --ask-pass -K
2. softether_add_ipsec.yaml - add L2TP/IPSec to SoftEther. Usage example: ansible-playbook -i put_your_vps_ip_here, softether_add_ipsec.yaml -u root --ask-pass -K


