## Overview

The Siemens IDEA environment is being virtualized by PMACS, within their vSphere server environment. For each version of IDEA, you'll need to establish two VMs: one for the Windows environment, and one for the Linux environment. 

## Communicating with PMACS to make requests

Please use the PMACS ticket system [http://helpdesk.pmacs.upenn.edu]([http://helpdesk.pmacs.upenn.edu). In each section below where a ticket might be required, please use the exact ticket template provided. If your ticket seems to be not progressing, let Dylan know and he can contact Jerry at PMACS to help triage.

## Getting an account:

You'll first need a PMACS account (ask Dylan to file a ticket for you). Once you have that, you can enter the ticket system. To create a new user for the vSphere system (the management system for the VMs), file a ticket as follows:

* Ticket Description: New user setup for Robust Methods of Magnetic Resonance (RMMR)
* PennKey:
* Group: VPN-rad-tisdal

## Setting up a new virtual machine

### Instantiating the VMs
You'll need to request both the Windows and Linux VMs associated with the version of IDEA you'd like to have setup. For this, you can use a ticket like this:

* Ticket Description: New VM setup for Robust Methods of Magnetic Resonance (RMMR)
* Windows Operating System: Windows 10 or Windows 7
* Windows Template: *copy from list below*
* Linux Template: *copy from list below*

Here's a list of the templates associated with each IDEA verson

|IDEA Version	| Windows					| Linux 					|
| ----		| ----						| ----						|
| N4VE11C	| RAD-MRI_VE11C_Distribution_Win7_Template 	|  RAD-MRI_VE11C_linux_win7_20160120_mars	|
| NXVA30A	| RAD-MRI_XA30A_DistributionOVF_win10_Template 	|  RAD-MRI_XA30A_DistributionOVF_linux_win10_Template	|

### Configuring the VMs

Stuff about config scripts goes here

## Resetting the virtual machines

If something goes wrong, you can always request PMACS to reset the VM. **THIS WILL ERASE EVERYTHING ON THE MACHINE** so make sure your code is committed and pushed to GitHub. To request a reset, please use the following ticket format:


* Ticket Description: Re-initialize VM for Robust Methods of Magnetic Resonance (RMMR)
* Name of VM(s) to delete
* Windows Operating System: Windows 10 or Windows 7
* Windows Template: *copy from list above* 
* Linux Template: *copy from list above*


## Accessing the manuals
