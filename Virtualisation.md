<div align="center">
<img style="width:45%" src="imgs/tcclogo.jpg" />
</div>

## Contents

1. [Introduction](README.md#introduction)
   - [Contributing](README.md##contributing)
2. [Communities](Communities.md)
3. [Business/Career](Communities.md#business)
4. [Services](README.md#services)
5. [Software](README.md#software)
6. [Programming](Programming.md)
7. [Ethics, Law & Professionalism](Ethics_Law_Professionalism.md)
   - [Ethics](Ethics_Law_Professionalism.md#ethics)
   - [Professionalism & Standards](Ethics_Law_Professionalism.md#standards)
   - [Law](Ethics_Law_Professionalism.md#law)
8. [Learning Resources](README.md#education)
9. [Linux Distributions](README.md#linux)
10. [Electronics](Electronics.md)
11. [Hypervisors and virtual machines](Virtualisation.md#virtualisation)
    - [Andrew Hancock, VMware vExpert PRO](Virtualisation.md#andrewhancock)
12. [Cyber Security Resources](CyberSecurity.md)
13. [Other Interesting Stuff](README.md#misc)
# Virtualisation List

#### Networking
1. [What is Mesh Topology?](https://fossbytes.com/what-is-mesh-topology-advantages-and-disadvantages-of-mesh-topology/)
2. [Types of Network Topology](https://www.educba.com/types-of-network-topology/)
3. [Network topologies, protocols and layers](https://www.bbc.co.uk/bitesize/guides/z666pbk/revision/2)

## Hypervisors and virtual machines  <a name="virtualisation"></a>

Ontop of the great VMware resources below there are other hypervisors for running containers and virtual machines.

Hypervisors are classified as Type 1 or Type 2 hypervisors. Type 1 are often known as bare metal hypervisors. It's installed on bare metal, e.g. it is not installed as an application on top of an operating system. A Type 2 hypervisor is an application which is installed on the operating system.
Type 2 Hypervisors can be SLOW.  In most reviews and experience, they perform at roughly 30-40% hardware capability.  That means an Guest Operating Systems in a virtual machine hosted on a Type 2 hyperviosor will likely perform at best like it has an 800 MHz CPU if you have 2 GHz physical CPU. 

If you use a Type 1 Hypervisor, you get much better performance (based on experience and reviews) typically get 80-90% hardware capability - so that same virtual machines hosted on the same 2 GHz CPU should operate more like it has a 1.6 GHz CPU instead of 800 Mhz. 

Here are some type 1 and type 2 hypervisors.

Type 1 (Bare Metal Hypervisors)

1. [Proxmox](http://www.proxmox.com) - A Free version of the commercial Proxmox hypervisor
2. [Nutanix CE](https://www.nutanix.com/products/community-edition) - A free version of the Nutanix HCI platform
3. [Oracle VM Server](https://www.oracle.com/virtualization/vm-server-for-x86/) - Commercial Type 1 hypervisor 
4. [XCP-ng](https://xcp-ng.org/) - Based on Xen Server - Available on GitHub.
5. [Citrix Hypervisor](https://www.citrix.com/en-gb/products/citrix-hypervisor/) - Originally based on Xen Server. Commercial version by Citrix.
6. [Microsoft Windows Server 2019](https://www.microsoft.com/en-gb/windows-server) - Hyper-V can be enabled as a role in Windows Server. This is a Type 1 hypervisor. - Available for free if a Student of The Department of Computer Science and Technology.
7. [Microsoft Hyper-V Server](https://www.microsoft.com/en-us/evalcenter/evaluate-hyper-v-server-2019) - Not to be confused with Windows Server. This is a Type 1 Hypervisor, and is just server core Hyper-V with no GUI. - Available for free if a Student of The Department of Computer Science and Technology.
8. [Microsoft Windows 10 Client Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/) - Hyper-V can be enabled in Windows 10 Pro and above. This is a Type 1 Hypervisor. - Available for free if a Student of The Department of Computer Science and Technology.
9. [VMware vSphere Hypervisor (ESXi)](https://my.vmware.com/en/web/vmware/evalcenter?p=free-esxi7) - Available for free, or full version - Available for free if a Student of The Department of Computer Science and Technology. All this software is FREE here - [VMware IT Academy Program](https://www.vmware.com/uk/company/it-academy.html) 
10. [KVM/QEmu](https://www.linux-kvm.org/page/Main_Page) - KVM is built into the linux kernel, just like Hyper-V in Windows

There are many frontends / management tools for KVM, including but not limited to

1. [Gnome Boxes](https://wiki.gnome.org/Apps/Boxes)
2. [virt-manager](https://virt-manager.org/)

furthermore, if you're system supports VT-d you can pass through your video card, or other pci device to use within your vm

1. [GPU Passthrough](https://github.com/bryansteiner/gpu-passthrough-tutorial)

Type 2

1. [Oracle Virtualbox](https://www.virtualbox.org/) - A Free alternative to VMware Workstation for all platforms
2. [VMware Fusion for Apple Mac](https://www.vmware.com/uk/products/fusion.html) - Type 2 Hypervisor for Apple Mac - Available for free if a Student of The Department of Computer Science and Technology. All this software is FREE here - [VMware IT Academy Program](https://www.vmware.com/uk/company/it-academy.html) 
3. [VMware Workstation](https://www.vmware.com/uk/products/workstation-pro.html) - Type 2 Hypervisor for Linux and Windows - Available for free if a Student of The Department of Computer Science and Technology. All this software is FREE here - [VMware IT Academy Program](https://www.vmware.com/uk/company/it-academy.html) 
4. [VMware Player](https://www.vmware.com/uk/products/workstation-player.html) - Type 2 Hypervosor for Linux and Windows - Available for free if a Student of The Department of Computer Science and Technology. All this software is FREE here - [VMware IT Academy Program](https://www.vmware.com/uk/company/it-academy.html) 
5. [Parallels Desktop 16 for Mac](https://www.parallels.com/uk/products/desktop/) - Type 2 Hypervisor for Mac.



## Andrew Hancock, Cyrus Computer Consultants Ltd <a name="andrewhancock"></a>
Andrew Hancock is VMware & Virtualisation Consultant in Apps, Servers & Storage at [Cyrus Computer Consultants Ltd.](https://www.cyrus-consultants.co.uk/) He also has a long list of VMware and Virtualisations articles, a passionate VMware Technical Architect, and VMware vExpert PRO. He has won over 40 [Experts Exchange Awards](https://www.experts-exchange.com/members/hanccocka.html) and is Overall Leader at [Experts Exchange](https://www.experts-exchange.com/) Experts Exchange - The Original Tech Community™ - Formed in 1996, Experts Exchange (EE) is one of the oldest online communities in the world. For 25 years, tech problem-solvers worldwide have gathered on EE to share knowledge and help each other succeed.

His articles are reproduced here for your reading pleasure. If you want to discuss anything VMware, then ask him! He will only be too happy to oblige. NFR VMware software is available via the [VMUG Advantage+Program](https://www.vmug.com/membership/vmug-advantage-membership/). If you are a Student in Full Time Education it can be obtained from the [VMware IT Academy Program](https://www.vmware.com/uk/company/it-academy.html) 
1. [How to Backup an ESXi installation on an USB Flash Drive or SD card for security or redundancy.](https://www.experts-exchange.com/A_5409.html)
2. [VMware ESX/ESXi Backup Guide](https://www.experts-exchange.com/A_5414.html)
3. [HOW TO: Improve the transfer rate of a Physical to Virtual (P2V) Virtual to Virtual Conversion (V2V) using VMware vCenter Converter Standalone 5.0](https://www.experts-exchange.com/articles/9131/HOW-TO-Improve-the-transfer-rate-of-a-Physical-to-Virtual-P2V-Virtual-to-Virtual-Conversion-V2V-using-VMware-vCenter-Converter-Standalone-5-0.html)
4. [HOW TO: Enable Jumbo Frames on a VMware vSphere Hypervisor (ESXi 5.0) host server using the VMware vSphere Client](https://www.experts-exchange.com/articles/9132/HOW-TO-Enable-Jumbo-Frames-on-a-VMware-vSphere-Hypervisor-ESXi-5-0-host-server-using-the-VMware-vSphere-Client.html)
5. [HOW TO: Suppress Configuration Issues and Warnings Alert displayed in Summary status for ESXi 4.1 U2 or ESXi 5.0 after enabling SSH or ESXi Shell](https://www.experts-exchange.com/articles/9151/HOW-TO-Suppress-Configuration-Issues-and-Warnings-Alert-displayed-in-Summary-status-for-ESXi-4-1-U2-or-ESXi-5-0-after-enabling-SSH-or-ESXi-Shell.html)
6. [HOW TO: Suppress Configuration Issues and Warnings Alerts after enabling vSphere HA in a VMware vSphere Cluster](https://www.experts-exchange.com/articles/9157/HOW-TO-Suppress-Configuration-Issues-and-Warnings-Alerts-after-enabling-vSphere-HA-in-a-VMware-vSphere-Cluster.html)
7. [HOW TO: Add Local Storage (e.g. a SATA disk) as a Raw Disk Mapping (RDM) or Mapped RAW LUN to a virtual machine hosted on ESXi](https://www.experts-exchange.com/articles/9174/HOW-TO-Add-Local-Storage-e-g-a-SATA-disk-as-a-Raw-Disk-Mapping-RDM-or-Mapped-RAW-LUN-to-a-virtual-machine-hosted-on-ESXi.html)
8. [HOW TO: Add an iSCSI Software Adaptor and Create an iSCSI Multipath Network in VMware vSphere Hypervisor ESXi 4.1](https://www.experts-exchange.com/articles/9209/HOW-TO-Add-an-iSCSI-Software-Adaptor-and-Create-an-iSCSI-Multipath-Network-in-VMware-vSphere-Hypervisor-ESXi-4-html)
9. [HOW TO: Clone or Copy a virtual machine in VMware vSphere Hypervisor ESX/ESXi 4.x or ESXi 5.0](https://www.experts-exchange.com/articles/9249/HOW-TO-Clone-or-Copy-a-virtual-machine-in-VMware-vSphere-Hypervisor-ESX-ESXi-4-x-or-ESXi-5-0.html)
10. [HOW TO: Add an iSCSI Software Adaptor and Create an iSCSI Multipath Network in VMware vSphere Hypervisor ESXi 5.0](https://www.experts-exchange.com/articles/9250/HOW-TO-Add-an-iSCSI-Software-Adaptor-and-Create-an-iSCSI-Multipath-Network-in-VMware-vSphere-Hypervisor-ESXi-5-0.html)
11. [HOW TO: Tutorial Video - Install VMware Tools for Linux on a VMware Linux virtual machine](https://www.experts-exchange.com/articles/9331/HOW-TO-Tutorial-Video-Install-VMware-Tools-for-Linux-on-a-VMware-Linux-virtual-machine.html)
12. [HOW TO: Add and Connect a USB Device to a Virtual Machine hosted on VMware vSphere Hypervisor ESX 4.1 ESXi 4.1](https://www.experts-exchange.com/articles/9349/HOW-TO-Add-and-Connect-a-USB-Device-to-a-Virtual-Machine-hosted-on-VMware-vSphere-Hypervisor-ESX-4-1-ESXi-4-1-ESXi-5-0.html)
13. [HOW TO: Tag and Configure a storage device as a Solid State Disk (SSD) in VMware vSphere 5.0 or 5.1  (ESXi 5.0 or ESXi 5.1)](https://www.experts-exchange.com/articles/10133/HOW-TO-Tag-and-Configure-a-storage-device-as-a-Solid-State-Disk-SSD-in-VMware-vSphere-5-0-or-5-1-ESXi-5-0-or-ESXi-5-html)
14. [HOW TO: VMware Snapshots :- Be Patient](https://www.experts-exchange.com/articles/10300/HOW-TO-VMware-Snapshots-Be-Patient.html)
15. [HOW TO: P2V V2V for FREE - VMware vCenter Converter Standalone 5.0](https://www.experts-exchange.com/articles/10301/HOW-TO-P2V-V2V-for-FREE-VMware-vCenter-Converter-Standalone-5-0.html)
16. [HOW TO: Resize a VMware (VMDK) Virtual Disk](https://www.experts-exchange.com/articles/10302/HOW-TO-Resize-a-VMware-VMDK-Virtual-Disk.html)
17. [HOW TO: VCP 5](https://www.experts-exchange.com/articles/10303/HOW-TO-VCP-5.html)
18. [HOW TO: Performance Monitor vSphere 4.x or 5.0](https://www.experts-exchange.com/articles/10304/HOW-TO-Performance-Monitor-vSphere-4-x-or-5-0.html)
19. [HOW TO: Suppress Configuration Issues and Warnings Alerts after enabling vSphere HA in a VMware vSphere Cluster with only a single datastore](https://www.experts-exchange.com/articles/10333/HOW-TO-Suppress-Configuration-Issues-and-Warnings-Alerts-after-enabling-vSphere-HA-in-a-VMware-vSphere-Cluster-with-only-a-single-datastore.html)
20. [HOW TO: Use Dell OpenManage Server Administrator to Create and Manage a Virtual Disk (RAID Array) on a Dell PowerEdge Server with VMware vSphere 5.0 ESXi 5.0 installed.](https://www.experts-exchange.com/articles/10624/HOW-TO-Use-Dell-OpenManage-Server-Administrator-to-Create-and-Manage-a-Virtual-Disk-RAID-Array-on-a-Dell-PowerEdge-Server-with-VMware-vSphere-5-0-ESXi-5-0-installed.html)
21. [HOW TO: Create a Bootable USB Flash Drive for Installation of Windows Server 2012](https://www.experts-exchange.com/articles/10694/HOW-TO-Create-a-Bootable-USB-Flash-Drive-for-Installation-of-Windows-Server-2012.html)
22. [HOW TO: "Live Migrate" VMware Virtual Machines between ESX/ESXi hosts and/or datastores for FREE without licenses for vMotion or Storage vMotion](https://www.experts-exchange.com/articles/10718/HOW-TO-Live-Migrate-VMware-Virtual-Machines-between-ESX-ESXi-hosts-and-or-datastores-for-FREE-without-licenses-for-vMotion-or-Storage-vMotion.html)
23. [HOW TO: Configure Host Cache Configuration for your VMware vSphere 5.0 or 5.1 ESXi (5.0 or 5.1) Host Server](https://www.experts-exchange.com/articles/10844/HOW-TO-Configure-Host-Cache-Configuration-for-your-VMware-vSphere-5-0-or-5-1-ESXi-5-0-or-5-1-Host-Server.html)
24. [HOW TO: Install and Configure VMware vSphere Hypervisor 5.1 (ESXi 5.1)](https://www.experts-exchange.com/articles/11116/HOW-TO-Install-and-Configure-VMware-vSphere-Hypervisor-5-1-ESXi-5-html)
25. [HOW TO: Connect to the VMware vSphere Hypervisor 5.1 (ESXi 5.1) using the vSphere Client](https://www.experts-exchange.com/articles/11133/HOW-TO-Connect-to-the-VMware-vSphere-Hypervisor-5-1-ESXi-5-1-using-the-vSphere-Client.html)
26. [HOW TO: Create an ISO CD-ROM/DVD-ROM image (*.iso) and MD5 checksum signature](https://www.experts-exchange.com/articles/11394/HOW-TO-Create-an-ISO-CD-ROM-DVD-ROM-image-iso-and-MD5-checksum-signature-for-use-with-VMware-vSphere-Hypervisor-5-1-ESXi-5-html)
27. [HOW TO: P2V V2V for FREE - VMware vCenter Converter Standalone 5.1](https://www.experts-exchange.com/articles/11449/HOW-TO-P2V-V2V-for-FREE-VMware-vCenter-Converter-Standalone-5-html)
28. [HOW TO: Synchronize changes when completing a P2V or V2V with VMware vCenter Converter Standalone 5.1](https://www.experts-exchange.com/articles/11489/HOW-TO-Synchronize-changes-when-completing-a-P2V-or-V2V-with-VMware-vCenter-Converter-Standalone-5-html)
29. [HOW TO: Add a Dell EqualLogic PS Series Array (SAN) to System Center Virtual Machine Manager 2012 SP1 as a SMP Provider](https://www.experts-exchange.com/articles/11571/HOW-TO-Add-a-Dell-EqualLogic-PS-Series-Array-SAN-to-System-Center-Virtual-Machine-Manager-2012-SP1-as-a-SMP-Provider.html)
30. [HOW TO: Upload an ISO CD-ROM/DVD-ROM image to a VMware datastore for use with VMware vSphere Hypervisor 5.1 (ESXi 5.1) using the vSphere Client and checking its MD5 checksum signature is correct.](https://www.experts-exchange.com/articles/11650/HOW-TO-Upload-an-ISO-CD-ROM-DVD-ROM-image-to-a-VMware-datastore-for-use-with-VMware-vSphere-Hypervisor-5-1-ESXi-5-1-using-the-vSphere-Client-and-checking-its-MD5-checksum-signature-is-correct.html)
31. [HOW TO: Enable SSH Remote Access on a VMware vSphere Hypervisor 5.1 (ESXi 5.1)](https://www.experts-exchange.com/articles/11651/HOW-TO-Enable-SSH-Remote-Access-on-a-VMware-vSphere-Hypervisor-5-1-ESXi-5-html)
32. [HOW TO: Create your first Linux Virtual Machine on a VMware vSphere Hypervisor 5.1 (ESXi 5.1) Host Server](https://www.experts-exchange.com/articles/11849/HOW-TO-Create-your-first-Linux-Virtual-Machine-on-a-VMware-vSphere-Hypervisor-5-1-ESXi-5-1-Host-Server.html)
33. [HOW TO: Create your first Windows Virtual Machine on a VMware vSphere Hypervisor 5.1 (ESXi 5.1) Host Server](https://www.experts-exchange.com/articles/11869/HOW-TO-Create-your-first-Windows-Virtual-Machine-on-a-VMware-vSphere-Hypervisor-5-1-ESXi-5-1-Host-Server.html)
34. [HOW TO: Install VMware Tools for Windows on a VMware Windows virtual machine on a VMware vSphere Hypervisor 5.1 (ESXi 5.1) Host Server](https://www.experts-exchange.com/articles/11873/HOW-TO-Install-VMware-Tools-for-Windows-on-a-VMware-Windows-virtual-machine-on-a-VMware-vSphere-Hypervisor-5-1-ESXi-5-1-Host-Server.html)
35. [HOW TO: Migrate a Windows Server 2008 R2 Hyper-V Virtual Machine (VM) to a Windows Server 2012 Hyper-V host server](https://www.experts-exchange.com/articles/12274/HOW-TO-Migrate-a-Windows-Server-2008-R2-Hyper-V-Virtual-Machine-VM-to-a-Windows-Server-2012-Hyper-V-host-server.html)
36. [HOW TO: P2V V2V for FREE - VMware vCenter Converter Standalone 5.5](https://www.experts-exchange.com/articles/12358/HOW-TO-P2V-V2V-for-FREE-VMware-vCenter-Converter-Standalone-5-5.html)
37. [HOW TO: Install VMware Tools for Linux on a VMware Linux virtual machine on a VMware vSphere Hypervisor 5.1 (ESXi 5.1) Host Server](https://www.experts-exchange.com/articles/12369/HOW-TO-Install-VMware-Tools-for-Linux-on-a-VMware-Linux-virtual-machine-on-a-VMware-vSphere-Hypervisor-5-1-ESXi-5-1-Host-Server.html)
38. [HOW TO: Backup (Export) and Restore (Import) virtual machines to VMware vSphere Hypervisor 5.1 for FREE](https://www.experts-exchange.com/articles/12373/HOW-TO-Backup-Export-and-Restore-Import-virtual-machines-to-VMware-vSphere-Hypervisor-5-1-for-FREE.html)
39. [HOW TO: Upgrade from VMware vSphere Hypervisor ESXi 5.1 to VMware vSphere Hypervisor ESXi 5.5 for FREE](https://www.experts-exchange.com/articles/12378/HOW-TO-Upgrade-from-VMware-vSphere-Hypervisor-ESXi-5-1-to-VMware-vSphere-Hypervisor-ESXi-5-5-for-FREE.html)
40. [HOW TO: What's New in VMware vSphere Hypervisor 5.5 (ESXi 5.5)](https://www.experts-exchange.com/articles/12495/HOW-TO-What's-New-in-VMware-vSphere-Hypervisor-5-5-ESXi-5-5.html)
41. [HOW TO: Select the right answer to "I Moved It" or "I Copied It" in VMware vSphere (ESXi)](https://www.experts-exchange.com/articles/12515/HOW-TO-Select-the-right-answer-to-I-Moved-It-or-I-Copied-It-in-VMware-vSphere-ESXi.html)
42. [HOW TO: FAQ VMware P2V Troubleshooting](https://www.experts-exchange.com/articles/12555/HOW-TO-FAQ-VMware-P2V-Troubleshooting.html)
43. [HOW TO: Suppress Configuration Issues System logs on host are stored on non-persistent storage](https://www.experts-exchange.com/articles/12675/HOW-TO-Suppress-Configuration-Issues-System-logs-on-host-are-stored-on-non-persistent-storage.html)
44. [HOW TO: Configure and Replace the SSL Certificate on a VMware vSphere Hypervisor 5.1 (ESXi 5.1) Host Server](https://www.experts-exchange.com/articles/12699/HOW-TO-Configure-and-Replace-the-SSL-Certificate-on-a-VMware-vSphere-Hypervisor-5-1-ESXi-5-1-Host-Server.html)
45. [HOW TO: Enhance the performance "speed up" the VMware vSphere Web Client in 15 minutes](https://www.experts-exchange.com/articles/12935/HOW-TO-Enhance-the-performance-speed-up-the-VMware-vSphere-Web-Client-in-15-minutes.html)
46. [HOW TO: Shrink a VMware Virtual Machine Disk (VMDK) in 15 minutes](https://www.experts-exchange.com/articles/12938/HOW-TO-Shrink-a-VMware-Virtual-Machine-Disk-VMDK-in-15-minutes.html)
47. [HOW TO: Convert and Migrate virtual machines and disks to Hyper-V and Windows Azure](https://www.experts-exchange.com/articles/13415/HOW-TO-Convert-and-Migrate-virtual-machines-and-disks-to-Hyper-V-and-Windows-Azure.html)
48. [HOW TO: Fix the Error loading /s.v00 Fatal error: 33 (Inconsistent data) in the VMware vSphere Hypervisor](https://www.experts-exchange.com/articles/13595/HOW-TO-Fix-the-Error-loading-s-v00-Fatal-error-33-Inconsistent-data-in-the-VMware-vSphere-Hypervisor.html)
49. [HOW TO: P2V V2V for FREE - VMware vCenter Converter Standalone 5.5.1](https://www.experts-exchange.com/articles/13778/HOW-TO-P2V-V2V-for-FREE-VMware-vCenter-Converter-Standalone-5-5-html)
50. [HOW TO: P2V V2V for FREE - VMware vCenter Converter Standalone 5.5.2 - OpenSSL HeartBleed Fix included in this version](https://www.experts-exchange.com/articles/13923/HOW-TO-P2V-V2V-for-FREE-VMware-vCenter-Converter-Standalone-5-5-2-OpenSSL-HeartBleed-Fix-included-in-this-version.html)
51. [HOW TO: Shrink or Reduce a VMware Virtual Machine Disk (VMDK) using VMware vCenter Converter Standalone v5.5.2](https://www.experts-exchange.com/articles/14299/HOW-TO-Shrink-or-Reduce-a-VMware-Virtual-Machine-Disk-VMDK-using-VMware-vCenter-Converter-Standalone-v5-5-2.html)
52. [HOW TO: Migrate a VMware vSphere virtual machine to the Cloud (hosted on Windows Azure)](https://www.experts-exchange.com/articles/14799/HOW-TO-Migrate-a-VMware-vSphere-virtual-machine-to-the-Cloud-hosted-on-Windows-Azure.html)
53. [HOW TO: Create a Windows Azure Free Trial subscription](https://www.experts-exchange.com/articles/14859/HOW-TO-Create-a-Windows-Azure-Free-Trial-subscription.html)
54. [HOW TO: Quickly Setup a NetApp FAS2520 Filer SAN/NAS Storage System](https://www.experts-exchange.com/articles/14939/HOW-TO-Quickly-Setup-a-NetApp-FAS2520-Filer-SAN-NAS-Storage-System.html)
55. [HOW TO: Configure basic networking on a VMware vSphere Hypervisor 5.1 (ESXi 5.1) Host Server](https://www.experts-exchange.com/articles/15841/HOW-TO-Configure-basic-networking-on-a-VMware-vSphere-Hypervisor-5-1-ESXi-5-1-Host-Server.html)
56. [HOW TO: P2V V2V for FREE - VMware vCenter Converter Standalone 5.5.3 - Shellshock "BASH" Fix included in this version](https://www.experts-exchange.com/articles/16939/HOW-TO-P2V-V2V-for-FREE-VMware-vCenter-Converter-Standalone-5-5-3-Shellshock-BASH-Fix-included-in-this-version.html)
57. [HOW TO: Fix An error has occurred adding datastores to an ESXi 5.x host](https://www.experts-exchange.com/articles/17304/HOW-TO-Fix-An-error-has-occurred-adding-datastores-to-an-ESXi-5-x-host.html)
58. [HOW TO: Migrate physical virtual and cloud based workloads with real-time replication to VMware vSphere (ESXi) using Double-Take MOVE](https://www.experts-exchange.com/articles/17312/HOW-TO-Migrate-physical-virtual-and-cloud-based-workloads-with-real-time-replication-to-VMware-vSphere-ESXi-using-Double-Take-MOVE.html)
59. [HOW TO: Fix a broken VMware vSphere Data Protection (VDP) Appliance](https://www.experts-exchange.com/articles/17327/HOW-TO-Fix-a-broken-VMware-vSphere-Data-Protection-VDP-Appliance.html)
60. [HOW TO: Fix the VMware Data Protection error - VDP: [001] The most recent checkpoint for the VDP appliance is outdated](https://www.experts-exchange.com/articles/17333/HOW-TO-Fix-the-VMware-Data-Protection-error-VDP-001-The-most-recent-checkpoint-for-the-VDP-appliance-is-outdated.html)
61. [HOW TO: Create a VMware vCloud Air Virtual Private Cloud OnDemand and receive $1000 free service credits](https://www.experts-exchange.com/articles/17420/HOW-TO-Create-a-VMware-vCloud-Air-Virtual-Private-Cloud-OnDemand-and-receive-1000-free-service-credits.html)
62. [HOW TO: P2V V2V for FREE to Hyper-V -  Microsoft Virtual Machine Converter 3.1](https://www.experts-exchange.com/articles/17453/HOW-TO-P2V-V2V-for-FREE-to-Hyper-V-Microsoft-Virtual-Machine-Converter-3-html)
63. [HOW TO: Convert a physical server or virtual server (P2V/V2V) to Microsoft Hyper-V using Microsoft Virtual Machine Converter 3.1](https://www.experts-exchange.com/articles/17461/HOW-TO-Convert-a-physical-server-or-virtual-server-P2V-V2V-to-Microsoft-Hyper-V-using-Microsoft-Virtual-Machine-Converter-3-html)
64. [HOW TO: ENABLE and RUN Microsoft Hyper-V in a VMware vSphere Virtual Machine](https://www.experts-exchange.com/articles/17470/HOW-TO-ENABLE-and-RUN-Microsoft-Hyper-V-in-a-VMware-vSphere-Virtual-Machine.html)
65. [HOW TO: Set up a lab environment for vSAN using VMware Workstation](https://www.experts-exchange.com/articles/17475/HOW-TO-Set-up-a-lab-environment-for-vSAN-using-VMware-Workstation.html)
66. [HOW TO: Install and Configure VMware vSphere Hypervisor 6.0 (ESXi 6.0)](https://www.experts-exchange.com/articles/17527/HOW-TO-Install-and-Configure-VMware-vSphere-Hypervisor-6-0-ESXi-6-0.html)
67. [HOW TO: Connect to the VMware vSphere Hypervisor 6.0 (ESXi 6.0) using the vSphere Client (C# client)](https://www.experts-exchange.com/articles/17528/HOW-TO-Connect-to-the-VMware-vSphere-Hypervisor-6-0-ESXi-6-0-using-the-vSphere-Client-C-client.html)
68. [HOW TO: Deploy and Install the VMWARE vCenter Server Appliance 6.0 (VCSA 6.0)](https://www.experts-exchange.com/articles/17529/HOW-TO-Deploy-and-Install-the-VMWARE-vCenter-Server-Appliance-6-0-VCSA-6-0.html)
69. [HOW TO: Fix the missing VMware vCenter Orchestrator Web Client Plugin from the vSphere Web Client](https://www.experts-exchange.com/articles/18349/HOW-TO-Fix-the-missing-VMware-vCenter-Orchestrator-Web-Client-Plugin-from-the-vSphere-Web-Client.html)
70. [HOW TO: P2V V2V for FREE - VMware vCenter Converter Standalone 6.0](https://www.experts-exchange.com/articles/18433/HOW-TO-P2V-V2V-for-FREE-VMware-vCenter-Converter-Standalone-6-0.html)
71. [12 commercial software backup products for VMware vSphere Hypervisor (ESXi) you should be evaluating today](https://www.experts-exchange.com/articles/18442/12-commercial-software-backup-products-for-VMware-vSphere-Hypervisor-ESXi-you-should-be-evaluating-today.html)
72. [HOW TO: Upgrade VMware ESXi 5.1 to ESXi 6.0 in 5 easy steps](https://www.experts-exchange.com/articles/18799/HOW-TO-Upgrade-VMware-ESXi-5-1-to-ESXi-6-0-in-5-easy-steps.html)
73. [HOW TO: Upgrade VMware ESXi 5.5 to ESXi 6.0 in 5 easy steps](https://www.experts-exchange.com/articles/18819/HOW-TO-Upgrade-VMware-ESXi-5-5-to-ESXi-6-0-in-5-easy-steps.html)
74. [HOW TO: Update VMware ESXi 6.0.0 GA to ESXi 6.0.0b in 5 easy steps](https://www.experts-exchange.com/articles/18820/HOW-TO-Update-VMware-ESXi-6-0-0-GA-to-ESXi-6-0-0b-in-5-easy-steps.html)
75. [HOW TO: Upgrade VMware ESXi 5.5 to VMware ESXi 6.0 using an ISO image](https://www.experts-exchange.com/articles/18839/HOW-TO-Upgrade-VMware-ESXi-5-5-to-VMware-ESXi-6-0-using-an-ISO-image.html)
76. [HOW TO: Install and Configure the VMware vSphere vCenter Server Appliance (VCSA) 5.5](https://www.experts-exchange.com/articles/18900/HOW-TO-Install-and-Configure-the-VMware-vSphere-vCenter-Server-Appliance-VCSA-5-5.html)
77. [HOW TO: Upgrade from vCenter Server Appliance (VCSA) 5.5 to 6.0](https://www.experts-exchange.com/articles/18919/HOW-TO-Upgrade-from-vCenter-Server-Appliance-VCSA-5-5-to-6-0.html)
78. [HOW TO: Install and Configure VMware vSphere vCenter Server 5.5 for Windows](https://www.experts-exchange.com/articles/18939/HOW-TO-Install-and-Configure-VMware-vSphere-vCenter-Server-5-5-for-Windows.html)
79. [HOW TO: Upgrade from vCenter Server 5.5 to 6.0](https://www.experts-exchange.com/articles/18959/HOW-TO-Upgrade-from-vCenter-Server-5-5-to-6-0.html)
80. [HOW TO: Install and Configure VMware vSphere vCenter Server 6.0 for Windows](https://www.experts-exchange.com/articles/19139/HOW-TO-Install-and-Configure-VMware-vSphere-vCenter-Server-6-0-for-Windows.html)
81. [HOW TO: Install and Configure VMware vSphere Update Manager (VUM) 6.0](https://www.experts-exchange.com/articles/19159/HOW-TO-Install-and-Configure-VMware-vSphere-Update-Manager-VUM-6-0.html)
82. [HOW TO: Add VMware vSphere Hypervisor ESXi Hosts to VMware vSphere vCenter Server 6.0](https://www.experts-exchange.com/articles/19181/HOW-TO-Add-VMware-vSphere-Hypervisor-ESXi-Hosts-to-VMware-vSphere-vCenter-Server-6-0.html)
83. [HOW TO: Upgrade VMware ESXi 5.1 and ESXi 5.5 to ESXi 6.0 with VMware Update Manager (VUM)](https://www.experts-exchange.com/articles/19219/HOW-TO-Upgrade-VMware-ESXi-5-1-and-ESXi-5-5-to-ESXi-6-0-with-VMware-Update-Manager-VUM.html)
84. [HOW TO: Update (Patch) VMware ESXi 6.0.0 GA to ESXi 6.0.0b with VMware Update Manager (VUM)](https://www.experts-exchange.com/articles/19279/HOW-TO-Update-Patch-VMware-ESXi-6-0-0-GA-to-ESXi-6-0-0b-with-VMware-Update-Manager-VUM.html)
85. [HOW TO: P2V V2V for FREE - VMware vCenter Converter Standalone 6.1](https://www.experts-exchange.com/articles/25539/HOW-TO-P2V-V2V-for-FREE-VMware-vCenter-Converter-Standalone-6-html)
86. [HOW TO: Fix Error code: ERR_CONNECTION_CLOSED when connecting to VMware vSphere Data Protection 5.x and 6.0.x using current versions of Internet Explorer Chrome and Firefox](https://www.experts-exchange.com/articles/26900/HOW-TO-Fix-Error-code-ERR-CONNECTION-CLOSED-when-connecting-to-VMware-vSphere-Data-Protection-5-x-and-6-0-x-using-current-versions-of-Internet-Explorer-Chrome-and-Firefox.html)
87. [HOW TO: Install and Configure VMware vSphere Hypervisor 6.5 (ESXi 6.5)](https://www.experts-exchange.com/articles/28863/HOW-TO-Install-and-Configure-VMware-vSphere-Hypervisor-6-5-ESXi-6-5.html)
88. [HOW TO: Connect to the VMware vSphere Hypervisor 6.5 (ESXi 6.5) using the vSphere (HTML5 Web) Host Client 6.5](https://www.experts-exchange.com/articles/28864/HOW-TO-Connect-to-the-VMware-vSphere-Hypervisor-6-5-ESXi-6-5-using-the-vSphere-HTML5-Web-Host-Client-6-5.html)
89. [HOW TO: Create an ISO CD-ROM/DVD-ROM image (*.iso) and MD5 checksum signature](https://www.experts-exchange.com/articles/28865/HOW-TO-Create-an-ISO-CD-ROM-DVD-ROM-image-iso-and-MD5-checksum-signature-for-use-with-VMware-vSphere-Hypervisor-6-5-ESXi-6-5.html)
90. [HOW TO: Upload an ISO image to a VMware datastore for use with VMware vSphere Hypervisor 6.5 (ESXi 6.5) using the vSphere Host Client and checking its MD5 checksum signature is correct.](https://www.experts-exchange.com/articles/28867/HOW-TO-Upload-an-ISO-image-to-a-VMware-datastore-for-use-with-VMware-vSphere-Hypervisor-6-5-ESXi-6-5-using-the-vSphere-Host-Client-and-checking-its-MD5-checksum-signature-is-correct.html)
91. [HOW TO: Enable SSH Remote Access on a VMware vSphere Hypervisor 6.5 (ESXi 6.5)](https://www.experts-exchange.com/articles/28874/HOW-TO-Enable-SSH-Remote-Access-on-a-VMware-vSphere-Hypervisor-6-5-ESXi-6-5.html)
92. [HOW TO: Suppress Configuration Issues and Warnings Alert displayed in Summary status for ESXi 6.5 after enabling SSH or ESXi Shell](https://www.experts-exchange.com/articles/28875/HOW-TO-Suppress-Configuration-Issues-and-Warnings-Alert-displayed-in-Summary-status-for-ESXi-6-5-after-enabling-SSH-or-ESXi-Shell.html)
93. [HOW TO: Create your first Windows Virtual Machine on a VMware vSphere Hypervisor 6.5 (ESXi 6.5) Host Server](https://www.experts-exchange.com/articles/28876/HOW-TO-Create-your-first-Windows-Virtual-Machine-on-a-VMware-vSphere-Hypervisor-6-5-ESXi-6-5-Host-Server.html)
94. [HOW TO: Install VMware Tools for Windows on a VMware Windows virtual machine on a VMware vSphere Hypervisor 6.5 (ESXi 6.5) Host Server](https://www.experts-exchange.com/articles/28894/HOW-TO-Install-VMware-Tools-for-Windows-on-a-VMware-Windows-virtual-machine-on-a-VMware-vSphere-Hypervisor-6-5-ESXi-6-5-Host-Server.html)
95. [HOW TO: Deploy and Install the VMware vCenter Server Appliance 6.5 (VCSA 6.5)](https://www.experts-exchange.com/articles/28896/HOW-TO-Deploy-and-Install-the-VMware-vCenter-Server-Appliance-6-5-VCSA-6-5.html)
96. [HOW TO: Perform a Physical to Virtual (P2V) Conversion the easy way from a computer backup (image).](https://www.experts-exchange.com/articles/28939/HOW-TO-Perform-a-Physical-to-Virtual-P2V-Conversion-the-easy-way-from-a-computer-backup-image.html)
97. [HOW TO: P2V V2V for FREE - VMware vCenter Converter Standalone 6.2](https://www.experts-exchange.com/articles/31526/HOW-TO-P2V-V2V-for-FREE-VMware-vCenter-Converter-Standalone-6-2.html)
98. [HOW TO: Install and Configure VMware vSphere Hypervisor 6.7 (ESXi 6.7)](https://www.experts-exchange.com/articles/33122/HOW-TO-Install-and-Configure-VMware-vSphere-Hypervisor-6-7-ESXi-6-7.html)
99. [HOW TO: Connect to the VMware vSphere Hypervisor 6.7 (ESXi 6.7) using the vSphere (HTML5 Web) Host Client 6.7](https://www.experts-exchange.com/articles/33249/HOW-TO-Connect-to-the-VMware-vSphere-Hypervisor-6-7-ESXi-6-7-using-the-vSphere-HTML5-Web-Host-Client-6-7.html)
100. [HOW TO: Create an ISO CD-ROM/DVD-ROM image (*.iso) and MD5 checksum signature](https://www.experts-exchange.com/articles/33251/HOW-TO-Create-an-ISO-CD-ROM-DVD-ROM-image-iso-and-MD5-checksum-signature-for-use-with-VMware-vSphere-Hypervisor-6-7-ESXi-6-7.html)
101. [HOW TO: Upload an ISO image to a VMware datastore for use with VMware vSphere Hypervisor 6.7 (ESXi 6.7) using the vSphere Host Client and checking its MD5 checksum signature is correct.](https://www.experts-exchange.com/articles/33847/HOW-TO-Upload-an-ISO-image-to-a-VMware-datastore-for-use-with-VMware-vSphere-Hypervisor-6-7-ESXi-6-7-using-the-vSphere-Host-Client-and-checking-its-MD5-checksum-signature-is-correct.html)
102. [HOW TO: Enable SSH Remote Access on a VMware vSphere Hypervisor 6.7 (ESXi 6.7)](https://www.experts-exchange.com/articles/33849/HOW-TO-Enable-SSH-Remote-Access-on-a-VMware-vSphere-Hypervisor-6-7-ESXi-6-7.html)
103. [HOW TO: Suppress Configuration Issues and Warnings Alert displayed in Summary status for ESXi 6.7 after enabling SSH or ESXi Shell.](https://www.experts-exchange.com/articles/33850/HOW-TO-Suppress-Configuration-Issues-and-Warnings-Alert-displayed-in-Summary-status-for-ESXi-6-7-after-enabling-SSH-or-ESXi-Shell.html)
104. [HOW TO: P2V V2V for FREE - VMware vCenter Converter Standalone 6.2.0.1](https://www.experts-exchange.com/articles/33851/HOW-TO-P2V-V2V-for-FREE-VMware-vCenter-Converter-Standalone-6-2-0-html)
105. [HOW TO: Update VMware ESXi 6.7 GA to ESXi 6.7U3(a) in 5 easy steps](https://www.experts-exchange.com/articles/33852/HOW-TO-Update-VMware-ESXi-6-7-GA-to-ESXi-6-7U3-a-in-5-easy-steps.html)
106. [HOW TO: Update VMware ESXi 6.7 GA to ESXi 6.7U3(a) direct from VMware.](https://www.experts-exchange.com/articles/33853/HOW-TO-Update-VMware-ESXi-6-7-GA-to-ESXi-6-7U3-a-direct-from-VMware.html)
107. [Part 1: HOW TO: Install and Configure VMware vSphere Hypervisor 7.0 (ESXi 7.0)](https://www.experts-exchange.com/articles/34051/HOW-TO-Install-and-Configure-VMware-vSphere-Hypervisor-7-0-ESXi-7-0.html)
108. [Part 2: HOW TO: Connect to the VMware vSphere Hypervisor 7.0 (ESXi 7.0) using the vSphere (HTML5 Web) Host Client 7.0](https://www.experts-exchange.com/articles/34113/HOW-TO-Connect-to-the-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-using-the-vSphere-HTML5-Web-Host-Client-7-0.html)
109. [Part 3: HOW TO: Create an ISO CD-ROM/DVD-ROM image (*.iso) and MD5 checksum signature](https://www.experts-exchange.com/articles/34130/HOW-TO-Create-an-ISO-CD-ROM-DVD-ROM-image-iso-and-MD5-checksum-signature-for-use-with-VMware-vSphere-Hypervisor-7-0-ESXi-7-0.html)
110. [Part 4: HOW TO: Upload an ISO image to a VMware datastore for use with VMware vSphere Hypervisor 7.0 (ESXi 7.0) using the vSphere Host Client and checking its MD5 checksum signature is correct.](https://www.experts-exchange.com/articles/34131/HOW-TO-Upload-an-ISO-image-to-a-VMware-datastore-for-use-with-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-using-the-vSphere-Host-Client-and-checking-its-MD5-checksum-signature-is-correct.html)
111. [Part 5: HOW TO: Enable SSH Remote Access on a VMware vSphere Hypervisor 7.0 (ESXi 7.0)](https://www.experts-exchange.com/articles/34132/HOW-TO-Enable-SSH-Remote-Access-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0.html)
112. [Part 6: HOW TO: Suppress Configuration Issues and Warnings Alert displayed in Summary status for ESXi 7.0 after enabling SSH or ESXi Shell.](https://www.experts-exchange.com/articles/34133/HOW-TO-Suppress-Configuration-Issues-and-Warnings-Alert-displayed-in-Summary-status-for-ESXi-7-0-after-enabling-SSH-or-ESXi-Shell.html)
113. [Part 7: HOW TO: Create your first Windows Virtual Machine on a VMware vSphere Hypervisor 7.0 (ESXi 7.0) Host Server](https://www.experts-exchange.com/articles/34134/HOW-TO-Create-your-first-Windows-Virtual-Machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
114. [Part 8: HOW TO: Install VMware Tools for Windows on a VMware Windows virtual machine on a VMware vSphere Hypervisor 7.0 (ESXi 7.0) Host Server](https://www.experts-exchange.com/articles/34135/HOW-TO-Install-VMware-Tools-for-Windows-on-a-VMware-Windows-virtual-machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
115. [Part 9: HOW TO: Create your first Linux Virtual Machine on a VMware vSphere Hypervisor 7.0 (ESXi 7.0) Host Server](https://www.experts-exchange.com/articles/34136/HOW-TO-Create-your-first-Linux-Virtual-Machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
116. [Part 10: HOW TO: Install VMware Tools for Linux on a VMware Linux virtual machine on a VMware vSphere Hypervisor 7.0 (ESXi 7.0) Host Server](https://www.experts-exchange.com/articles/34137/HOW-TO-Install-VMware-Tools-for-Linux-on-a-VMware-Linux-virtual-machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
117. [Part 11: HOW TO: Install open-vm-tools for Linux on a VMware Linux virtual machine on a VMware vSphere Hypervisor 7.0 (ESXi 7.0) Host Server](https://www.experts-exchange.com/articles/34138/HOW-TO-Install-open-vm-tools-for-Linux-on-a-VMware-Linux-virtual-machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
118. [Part 12: HOW TO: Update VMware ESXi 6.7 to ESXi 7.0 GA in 5 easy steps](https://www.experts-exchange.com/articles/34149/HOW-TO-Update-VMware-ESXi-6-7-to-ESXi-7-0-GA-in-5-easy-steps.html)
119. [HOW TO: What is a VMware vExpert?](https://www.experts-exchange.com/articles/34168/HOW-TO-What-is-a-VMware-vExpert.html)
120. [Part 13: HOW TO: Update VMware ESXi 6.7 to ESXi 7.0 GA direct from VMware.](https://www.experts-exchange.com/articles/34207/HOW-TO-Update-VMware-ESXi-6-7-to-ESXi-7-0-GA-direct-from-VMware.html)
121. [Part 14: HOW TO: P2V a Windows XP computer to VMware vSphere Hypervisor 7.0 (ESXi 7.0)](https://www.experts-exchange.com/articles/34208/HOW-TO-P2V-a-Windows-XP-computer-to-VMware-vSphere-Hypervisor-7-0-ESXi-7-0.html)
122. [HOW TO: Make Microsoft Hyper-V and VMware Workstation function side by side](https://www.experts-exchange.com/articles/34209/HOW-TO-Make-Microsoft-Hyper-V-and-VMware-Workstation-function-side-by-side.html)
123. [Part 15: HOW TO: Backup (Export) and Restore (Import) virtual machines to VMware vSphere Hypervisor 7.0 for FREE](https://www.experts-exchange.com/articles/34210/HOW-TO-Backup-Export-and-Restore-Import-virtual-machines-to-VMware-vSphere-Hypervisor-7-0-for-FREE.html)
124. [Part 16: HOW TO: Update VMware ESXi 7.0 GA to ESXi 7.0bs direct from VMware.](https://www.experts-exchange.com/articles/34247/HOW-TO-Update-VMware-ESXi-7-0-GA-to-ESXi-7-0bs-direct-from-VMware.html)
125. [Part 17: HOW TO: Update VMware ESXi 7.0 GA to ESXi 7.0b direct from VMware.](https://www.experts-exchange.com/articles/34248/HOW-TO-Update-VMware-ESXi-7-0-GA-to-ESXi-7-0b-direct-from-VMware.html)
126. [Part 18: HOW TO: Update VMware ESXi 7.0 GA to ESXi 7.0bs in 5 easy steps](https://www.experts-exchange.com/articles/34249/HOW-TO-Update-VMware-ESXi-7-0-GA-to-ESXi-7-0bs-in-5-easy-steps.html)
127. [Part 19: HOW TO: Update VMware ESXi 7.0 GA to ESXi 7.0b in 5 easy steps](https://www.experts-exchange.com/articles/34250/HOW-TO-Update-VMware-ESXi-7-0-GA-to-ESXi-7-0b-in-5-easy-steps.html)
128. [Part 20: HOW TO: Install and Configure VMware vSphere Hypervisor 7.0 (ESXi 7.0 ARM) on a Raspberry Pi 4](https://www.experts-exchange.com/articles/34931/HOW-TO-Install-and-Configure-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-ARM-on-a-Raspberry-Pi-4.html)
129. [Part 21: HOW TO: Deploy and Install VMware vSphere vCenter Server 7.0 (VCSA 7.0)](https://www.experts-exchange.com/articles/35011/HOW-TO-Deploy-and-Install-VMware-vSphere-vCenter-Server-7-0-VCSA-7-0.html)
130. [Part 22: HOW TO: Install and Connect a VMware vCenter Server 7.0 in linked mode.](https://www.experts-exchange.com/articles/35052/HOW-TO-Install-and-Connect-a-VMware-vCenter-Server-7-0-in-linked-mode.html)
131. [Part 23: HOW TO: BOOT VMware vSphere Hypervisor 7.0 (ESXi 7.0 ARM) from an iSCSI LUN for the Raspberry Pi 4](https://www.experts-exchange.com/articles/35132/HOW-TO-BOOT-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-ARM-from-an-iSCSI-LUN-for-the-Raspberry-Pi-4.html)
132. [Part 24: HOW TO: Update VMware ESXi 7.0U2 to ESXi 7.0U2a direct from VMware.](https://www.experts-exchange.com/videos/79032/HOW-TO-Update-VMware-ESXi-7-0U2-to-ESXi-7-0U2a-direct-from-VMware.html)
133. [Part 25: HOW TO: Update VMware ESXi 7.0U2 to ESXi 7.0U2a in 5 easy steps.](https://www.experts-exchange.com/articles/36038/HOW-TO-Update-VMware-ESXi-7-0U2-to-ESXi-7-0U2a-in-5-easy-steps.html)


### Hancock's VMware Half Hour HOW TO Video Series

In this series, which compliments the written articles above, Andrew Hancock demonstrates "HOW TO" on a variety of topics. All these videos are based on the previous written content at Experts Exchange.

In this short online course, there is a total of 7.5 hours of online videos from Part 1 to Part 22, taking you through the basics of VMware vSphere 7.0, from installation of the hypervisor (ESXi), creating Windows and Linux virtual machines, updating the ESXi hosts and installing and adding ESXi hosts to vCenter Server (the management server.)
This course is split over 22 parts, in bit size chunks, hosted by Andrew Hancock. If you have any questions or issues, then please consider posting a question on [Experts Exchange](https://www.experts-exchange.com/).

1. [Part 1: HOW TO: Install and Configure VMware vSphere Hypervisor 7.0 U2 (ESXi 7.0.2).](https://www.experts-exchange.com/videos/78972/HOW-TO-Install-and-Configure-VMware-vSphere-Hypervisor-7-0-U2-ESXi-7-0-2.html)
2. [Part 2: HOW TO: Connect to the VMware vSphere Hypervisor 7.0 U2 (ESXi 7.0.2) using the vSphere Host Client.](https://www.experts-exchange.com/videos/78992/HOW-TO-Connect-to-the-VMware-vSphere-Hypervisor-7-0U2-ESXi-7-0-2-using-the-vSphere-HTML5-Web-Host-Client-7-0.html)
3. [Part 3: HOW TO: HOW TO: Create an ISO CD-ROM/DVD-ROM image (.iso), and MD5 checksum signature, for use with ESXi 7.0.](https://www.experts-exchange.com/videos/79039/HOW-TO-Create-an-ISO-CD-ROM-DVD-ROM-image-iso-and-MD5-checksum-signature-for-use-with-VMware-vSphere-Hypervisor-7-0-ESXi-7-0.html)
4. [Part 4: HOW TO: Upload an ISO image to a VMware datastore for use with VMware vSphere Hypervisor 7.0.](https://www.experts-exchange.com/videos/79036/HOW-TO-Upload-an-ISO-image-to-a-VMware-datastore-for-use-with-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-using-the-vSphere-Host-Client-and-checking-its-MD5-checksum-signature-is-correct.html)
5. [Part 5: HOW TO: Enable SSH Remote Access on a VMware vSphere Hypervisor 7.0 (ESXi 7.0).](https://www.experts-exchange.com/videos/79037/HOW-TO-Enable-SSH-Remote-Access-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0.html)
6. [Part 6: HOW TO: Suppress Configuration Issues and Warnings Alert displayed in Summary status for ESXi 7.0.](https://www.experts-exchange.com/videos/79038/HOW-TO-Suppress-Configuration-Issues-and-Warnings-Alert-displayed-in-Summary-status-for-ESXi-7-0-after-enabling-SSH-or-ESXi-Shell.html)
7. [Part 7: HOW TO: Create your first Windows Virtual Machine on a VMware vSphere Hypervisor 7.0 (ESXi 7.0) Host Server.](https://www.experts-exchange.com/videos/79052/HOW-TO-Create-your-first-Windows-Virtual-Machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
8. [Part 8: HOW TO: Install VMware Tools for Windows on a VMware Windows virtual machine on a VMware vSphere Hypervisor 7.0 (ESXi 7.0) Host Server](https://www.experts-exchange.com/videos/79072/HOW-TO-Install-VMware-Tools-for-Windows-on-a-VMware-Windows-virtual-machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
9. [Part 9: HOW TO: Create your first Linux Virtual Machine Ubuntu 20.04 LTS Server on a VMware vSphere Hypervisor 7.0 (ESXi 7.0) Host Server.](https://www.experts-exchange.com/videos/79073/HOW-TO-Create-your-first-Linux-Virtual-Machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
10. [Part 10: HOW TO: Create your second Virtual Machine Ubuntu 20.04 LTS Desktop on a VMware vSphere Hypervisor 7.0 (ESXi 7.0) Host Server.](https://www.experts-exchange.com/videos/79074/HOW-TO-Create-your-second-Virtual-Machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
11. [Part 11: HOW TO: Install VMware Tools for Linux on a VMware Linux virtual machine on a VMware vSphere Hypervisor 7.0 (ESXi 7.0).](https://www.experts-exchange.com/videos/79092/HOW-TO-Install-VMware-Tools-for-Linux-on-a-VMware-Linux-virtual-machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
12. [Part 12: HOW TO: Install open-vm-tools for Linux on a VMware Linux virtual machine on a VMware vSphere Hypervisor 7.0 (ESXi 7.0).](https://www.experts-exchange.com/videos/79093/HOW-TO-Install-open-vm-tools-for-Linux-on-a-VMware-Linux-virtual-machine-on-a-VMware-vSphere-Hypervisor-7-0-ESXi-7-0-Host-Server.html)
13. [Part 13: HOW TO: Backup (Export) and Restore (Import) virtual machines to VMware vSphere Hypervisor 7.0 for free.](https://www.experts-exchange.com/videos/79094/HOW-TO-Backup-Export-and-Restore-Import-virtual-machines-to-VMware-vSphere-Hypervisor-7-0-for-FREE.html)
14. [Part 14: HOW TO: P2V a Windows XP computer to VMware vSphere Hypervisor 7.0 (ESXi 7.0).](https://www.experts-exchange.com/videos/79095/HOW-TO-P2V-a-Windows-operating-system-computer-to-VMware-vSphere-Hypervisor-7-0-ESXi-7-0.html)
15. [Part 15: HOW TO: Shrink or Reduce a VMware Virtual Machine Disk (VMDK) using VMware vCenter Converter Standalone v6.2.0.1.](https://www.experts-exchange.com/videos/79096/HOW-TO-Shrink-or-Reduce-a-VMware-Virtual-Machine-Disk-VMDK-using-VMware-vCenter-Converter-Standalone-v6-2-0-1.html)
16. [Part 16: HOW TO: Update VMware ESXi 7.0U2 to ESXi 7.0U2a direct from VMware.](https://www.experts-exchange.com/videos/79032/HOW-TO-Update-VMware-ESXi-7-0U2-to-ESXi-7-0U2a-direct-from-VMware.html)
17. [Part 17: HOW TO: Update VMware ESXi 7.0U2 to ESXi 7.0U2a in 5 easy steps.](https://www.experts-exchange.com/videos/79033/HOW-TO-Update-VMware-ESXi-7-0U2-to-ESXi-7-0U2a-in-5-easy-steps.html)
18. [Part 18: HOW TO: Update VMware ESXi 7U1 (7.0.1) to VMware ESXi 7U2a (7.0.2) using an ISO image.](https://www.experts-exchange.com/videos/79034/HOW-TO-Update-VMware-ESXi-7U1-7-0-1-to-VMware-ESXi-7U2a-7-0-2-using-an-ISO-image.html)
19. [Part 19: HOW TO: Update VMware ESXi 7.0U1 to ESXi 7.0U2a using VMware vSphere Lifecycle Manager (vLCM).](https://www.experts-exchange.com/videos/79035/HOW-TO-Update-VMware-ESXi-7-0U1-to-ESXi-7-0U2a-using-VMware-vSphere-Lifecycle-Manager-vLCM.html)
20. [Part 20: HOW TO: Rollback VMware vSphere Hypervisor 7.0 U2a using VMware Hypervisor Recovery Mode.](https://www.experts-exchange.com/videos/79012/HOW-TO-Rollback-VMware-vSphere-Hypervisor-7-0-U2a-using-VMware-Hypervisor-Recovery-Mode.html)
21. [Part 21: HOW TO: Deploy and Install VMware vSphere vCenter Server 7.0 (VCSA 7.0).](https://www.experts-exchange.com/videos/79152/HOW-TO-Deploy-and-Install-VMware-vSphere-vCenter-Server-7-0-VCSA-7-0.html)
22. [Part 22: HOW TO: Add VMware vSphere Hypervisor ESXi 7.0 Hosts to VMware vSphere vCenter Server 7.0.](https://www.experts-exchange.com/videos/79192/HOW-TO-Add-VMware-vSphere-Hypervisor-ESXi-7-0-Hosts-to-VMware-vSphere-vCenter-Server-7-0.html)
23. [Part 23: HOW TO: Update VMware vSphere vCenter Server 7.0 (VCSA 7.0) using the (VAMI) Appliance Management Interface.](https://www.experts-exchange.com/videos/79452/HOW-TO-Update-VMware-vSphere-vCenter-Server-7-0-VCSA-7-0-using-the-VAMI-Appliance-Management-Interface.html)
24. [Part 24: HOW TO: Cross vCenter Server vMotion (export) between standalone vCenter Servers 7.0 not linked to the current SSO domain.](https://www.experts-exchange.com/videos/79454/HOW-TO-Cross-vCenter-Server-vMotion-export-between-standalone-vCenter-Servers-7-0-not-linked-to-the-current-SSO-domain.html)
25. [Part 25: HOW TO: Add a Synology NAS providing NFS Storge to VMware vSphere Hypervisor ESXi 7.0.](https://www.experts-exchange.com/videos/79455/HOW-TO-Add-a-Synology-NAS-providing-NFS-Storge-to-VMware-vSphere-Hypervisor-ESXi-7-0.html)
26. [Part 26: HOW TO: Create a VMware vSphere Cluster add an EVC Baseline and then present a Synology NAS to multiple hosts in the cluster.](https://www.experts-exchange.com/videos/79456/HOW-TO-Create-a-VMware-vSphere-Cluster-add-an-EVC-Baseline-and-then-present-a-Synology-NAS-to-multiple-hosts-in-the-cluster.html)
27. [Part 27: HOW TO: Migrate VMware vCenter Server 7.0 in an enabled EVC VMware vSphere 7.0 Cluster of ESXi 7.0 hosts using "Andy's Towers of Hanoi solution"](https://www.experts-exchange.com/videos/79473/HOW-TO-Migrate-VMware-vCenter-Server-7-0-in-an-enabled-EVC-VMware-vSphere-7-0-Cluster-of-ESXi-7-0-hosts-using-Andy's-Towers-of-Hanoi-solution.html)
28. [Part 28: HOW TO: FIX the Warning System logs on host are stored on non-persistent storage, Move system logs to NFS shared storage.](https://www.experts-exchange.com/videos/79492/HOW-TO-FIX-the-Warning-System-logs-on-host-are-stored-on-non-persistent-storage-Move-system-logs-to-NFS-shared-storage.html)
29. [Part 29: HOW TO: FIX No coredump target has been configured. Host core dumps cannot be saved.](https://www.experts-exchange.com/videos/79493/HOW-TO-FIX-No-coredump-target-has-been-configured-Host-core-dumps-cannot-be-saved.html)
30. [Part 30: HOW TO: FIX VMware vSphere Hypervisor (ESXi) Host vulnerability L1 Terminal Fault’ (L1TF) Speculative-Execution in Intel processors: CVE-2018-3646, CVE-2018-3620, and CVE-2018-3615](https://www.experts-exchange.com/videos/79495/HOW-TO-FIX-VMware-vSphere-Hypervisor-ESXi-Host-vulnerability-L1-Terminal-Fault-L1TF-Speculative-Execution-in-Intel-processors-CVE-2018-3646-CVE-2018-3620-and-CVE-2018-3615.html)
31. [Part 31: HOW TO: Add a Synology NAS providing iSCSI Storage to VMware vSphere Hypervisor ESXi 7.0 Part 1](https://www.experts-exchange.com/videos/79513/HOW-TO-Add-a-Synology-NAS-providing-iSCSI-Storge-to-VMware-vSphere-Hypervisor-ESXi-7-0-Part-1.html)
32. [Part 32: HOW TO: Add a Synology NAS providing iSCSI Storage to VMware vSphere Hypervisor ESXi 7.0 Part 2](https://www.experts-exchange.com/videos/79514/HOW-TO-Add-a-Synology-NAS-providing-iSCSI-Storage-to-VMware-vSphere-Hypervisor-ESXi-7-0-Part-2.html)
32. [Part 33: HOW TO: Deploy and Use the Synology Storage Console for VMware to Add iSCSI LUNs and NFS exports to VMware vSphere Cluster ESXi Hosts](https://www.experts-exchange.com/videos/79512/HOW-TO-Deploy-and-Use-the-Synology-Storage-Console-for-VMware-to-Add-iSCSI-LUNs-and-NFS-exports-to-VMware-vSphere-Cluster-ESXi-Hosts.html)


