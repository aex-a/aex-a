![Header](header.png)

Git 󱓇 1970-01-01T00:00:00Z
󱞩  aex-a $ fastfetch


             .',;::::;,'.                 • SYSTEM INFORMATION
         .';:cccccccccccc:;,.             ROLE - NOC Technician II -> Junior SRE
      .;cccccccccccccccccccccc;.          CERT - RHCSA (ID: 250-187-358)
    .:cccccccccccccccccccccccccc:.        OS - openSUSE Tumbleweed / Fedora / RHEL 10
  .;ccccccccccccc;.:dddl:.;ccccccc;.      IAC - OpenTofu / Terraform / GCP
 .:ccccccccccccc;OWMKOOXMWd;ccccccc:.     AUTOMATION - Bash / Systemd-Timers / Cron
.:ccccccccccccc;KMMc;cc;xMMc;ccccccc:.    NETWORKING - OpenWRT / VPC / firewall-cmd / wg
,cccccccccccccc;MMM.;cc;;WW:;cccccccc,    SECURITY - SELinux / PCI Compliance / Lynis (CISOfy)
:cccccccccccccc;MMM.;cccccccccccccccc:    DISKS - BTRFS / XFS / LVM / LUKS
:ccccccc;oxOOOo;MMM000k.;cccccccccccc:    LOGIN MANAGER - Wayland
cccccc;0MMKxdd:;MMMkddc.;cccccccccccc;    
ccccc;XMO';cccc;MMM.;cccccccccccccccc'    
ccccc;MMo;ccccc;MMW.;ccccccccccccccc;     
ccccc;0MNc.ccc.xMMd;ccccccccccccccc;      
cccccc;dNMWXXXWM0:;cccccccccccccc:,       
cccccccc;.:odl:.;cccccccccccccc:,.        
ccccccccccccccccccccccccccccc:'.          
:ccccccccccccccccccccccc:;,.. 
 ':cccccccccccccccc::;,. 


## 🐧 feat/projects

### [ot-trek](https://github.com/aex-a/ot-trek) | `OpenTofu` `GCP` `IaC`
Architected a modular, scalable Google Cloud Platform environment entirely via Infrastructure as Code. 
Features strict SSH firewall rules and zero-touch deployment pipelines utilizing `metadata_startup_scripts`
for automated dependency injection.

### [tux-utils](https://github.com/aex-a/tux-utils) | `Bash` `Systemd` `Linux`
A suite of robust Bash utilities engineered for Linux environments.
**q-length.sh**: A dual-mode network socket/queue monitoring tool integrated directly as a native `systemd`
daemon with signal trapping (SIGINT/SIGTERM) for graceful shutdowns.
