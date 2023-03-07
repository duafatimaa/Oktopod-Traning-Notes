 # Difference Between RDP & KVM 
 RDP or Remote Desktop Protocol is the primary method by which Windows Systems can be remotely accessed for troubleshooting and is a software-driven method. KVM or Keyboard Video and Mouse on the other hand allows for the fast switching between many different systems but using the same keyboard, monitor and mouse for all. KVM is usually a hardware-driven system, with a junction box placed between the user and the systems in question- but there are some options that are enhanced by software. KVM also doesn't require an active network connection, so it can be very useful for using the same setup on multiple networks without having crosstalk. 
 # RDP 

Remote desktop protocol (RDP) is a secure network communications protocol developed by Microsoft. It enables network administrators to remotely diagnose problems that individual users encounter and gives users remote access to their physical work desktop computers. 

RDP can be used by employees working from home or traveling who need access to their work computers. RDP is also often used by support technicians who need to diagnose and repair a user's system remotely and by admins providing system maintenance. 

To use a remote desktop session a user or admin must employ RDP client software to connect to the remote Windows PC or server running RDP server software. A graphical user interface enables the remote user or admin to open applications and edit files as if they were sitting in front of their desktop. 

## Features of RDP 

RDP is a secure, interoperable protocol that creates secure connections between clients, servers and virtual machines. RDP works across different Windows OSes and devices and provides strong physical security through remote data storage. 

Noteworthy properties of RDP include the following: 

- smart card authentication 

- Bandwidth reduction; 

- the ability to use multiple displays; 

- the ability to disconnect temporarily without logging off; 

- RemoteFX virtualized GPU (graphics processing unit) support; 

- 128-bit encryption for mouse and keyboard data using RC4 encryption; 

- directs audio from a remote desktop to the user's computer; 

- redirects local files to a remote desktop; 

- local printers can be used in remote desktop sessions; 

- applications in the remote desktop session can access local ports; 

- shares clipboard between local and remote computers; 

- applications on a remote desktop can be run on a local computer; 

- supports Transport Layer Security; 

- improvements to RemoteApp; and 

RDP can support up to 64,000 independent channels for data transmission. Data can be encrypted using 128-bit keys. The bandwidth reduction feature optimizes the data transfer rate in low-speed connections. 

It is worth noting that not every RDP client supports all of these features. Additionally, a client might only support certain features when operating in enhanced session mode. 

## RDP use cases 

There are three main use cases for RDP. These include the following: 

- remote troubleshooting (either by a corporate help desk or by an individual who is trying to assist someone they know); 

- remote desktop access (such as being able to access a home or office PC while traveling); and 

- remote administration (being able to make remote configuration changes on network servers). 

## How does remote desktop protocol work? 

RDP provides remote access through a dedicated network channel. An RDP-enabled application or service packages the data to be transmitted, and the Microsoft Communications Service directs the data to an RDP channel. From there, the OS encrypts the RDP data and adds it to a frame so that it can be transmitted. 

The Terminal Server Device Redirector Driver handles all RDP activity. This kernel driver comprises subcomponents such as the RDP driver, which handles user interfaces, transfers, encryption, compression and framing. The transport driver is responsible for packaging the protocol sent across a TCP/IP network. 

# KVM

Kernel-based Virtual Machine (KVM) is a software feature that you can install on physical Linux machines to create virtual machines. A virtual machine is a software application that acts as an independent computer within another physical computer. It shares resources like CPU cycles, network bandwidth, and memory with the physical machine. KVM is a Linux operating system component that provides native support for virtual machines on Linux. It has been available in Linux distributions since 2007.  

## Why is KVM important? 

Kernel-based Virtual Machine (KVM) can turn any Linux machine into a bare-metal hypervisor. This allows developers to scale computing infrastructure for different operating systems without investing in new hardware. KVM frees server administrators from manually provisioning virtualization infrastructure and allows large numbers of virtual machines to be deployed easily in cloud environments.  

Businesses use KVM because of the following advantages. 

## High performance 

KVM is engineered to manage high-demanding applications seamlessly. All guest operating systems inherit the high performance of the host operating system—Linux. The KVM hypervisor also allows virtualization to be performed as close as possible to the server hardware, which further reduces process latency.  

## Security 

Virtual machines running on KVM enjoy security features native to the Linux operating system, including Security-Enhanced Linux (SELinux). This ensures that all virtual environments strictly adhere to their respective security boundaries to strengthen data privacy and governance.  

## Stability 

KVM has been widely used in business applications for more than a decade. It enjoys excellent support from a thriving open-source community. The source code that powers KVM is mature and provides a stable foundation for enterprise applications.  

## Cost efficiency 

KVM is free and open source, which means businesses do not have to pay additional licensing fees to host virtual machines.  

## Flexibility 

KVM provides businesses many options during installations, as it works with various hardware setups. Server administrators can efficiently allocate additional CPU, storage, or memory to a virtual machine with KVM. KVM also supports thin provisioning, which only provides the resources to the virtual machine when needed.  

## How does KVM work? 

Kernel-based Virtual Machine (KVM) requires a Linux kernel installation on a computer powered by a CPU that supports virtualization extensions. Specifically, KVM supports all x86 CPUs, a family of computer chips capable of processing the Intel x86 instruction language.  

## Linux kernel 

Linux kernel is the core of the open-source operating system. A kernel is a low-level program that interacts with computer hardware. It also ensures that software applications running on the operating system receive the required computing resources. Linux distributions, such as Red Hat Enterprise Linux, Fedora, and Ubuntu, pack the Linux kernel and additional programs into a user-friendly commercial operating system. 

## How to enable KVM 

Once you have installed the Linux kernel, you need to install the following additional software components on the Linux machine: 
- A host kernel module 
- A processor-specific module 
- An emulator 
- A range of other Linux packages for expanding KVM’s capabilities and performance.

## A host kernel modul.


A processor-specific module 

## An emulator 

A range of other Linux packages for expanding KVM’s capabilities and performance 

Once loaded, the server administrator creates a virtual machine via the command line tool or graphical user interface. KVM then launches the virtual machine as an individual Linux process. The hypervisor allocates every virtual machine with virtual memory, storage, network, CPU, and resources. 

## What is the difference between KVM and VMware? 

VMware is the software company that produces VMware ESXi, a commercially licensed virtualization solution. VMware hypervisors are used for enterprise applications, with virtual machines capable of handling heavy workloads. 

Kernel-based Virtual Machine (KVM) and VMware ESXi both provide virtualization infrastructure to deploy type 1 hypervisors on the Linux kernel. However, KVM is an open-source feature while VMware ESXi is available via commercial licenses. 

Organizations using VMware’s virtualization components enjoy professional support from its technical team. Meanwhile, KVM users rely on a vast open-source community to address potential issues.  

## How does AWS help with KVM? 

Amazon Linux 2 is an Amazon Web Services (AWS) Linux distribution that runs cloud applications in a stable, secure, and high-performance environment. Amazon Linux 2 is available as virtual machine images for development and testing on these virtualization platforms: Kernel-based Virtual Machine (KVM), Microsoft Hyper-V, Oracle VM VirtualBox, and VMware ESXi. 

## Here are other benefits of Amazon Linux 2: 

- Amazon Linux 2 comes with packages and configurations for easy integration with other AWS services 

- Developers can use Amazon Linux 2 for on-premises testing to support local development 

- Amazon Linux 2 automatically applies security patches without rebooting 

- Organizations using Amazon Linux 2 enjoy long-term support for security updates and five years of support for bug fixes 
