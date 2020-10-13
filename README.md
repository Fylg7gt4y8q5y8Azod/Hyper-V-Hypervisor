# Hyper-V-Hypervisor
How to disable Hypervisor in a Win 10 Home 64 bit computer ?

The issue is that   a) Hypervisor is not even supposed to be compatible with Win 10 Home 64 bit.  
Hence:  b) Why, who or what makes it turn on and makes it crash on my computer? 

Other: I was referred here by Microsoft, which apparently does not answer questions.

Other2: Using a powershell query such as
Get-WindowsOptionalFeature -Online |? FeatureName -match "Hyper" 
tells me that 
"HypervisorPlatform"
"State: Enabled"

Why would it be enabled, when it is not compatible with Win 10 64bit Home? 

Using a command like "Disable-Hypervisor" or "Uninstall-Hypervisor" or "delete Hypervisor" does not work. 

Powershell commands are not explained and are both inadequate and logically inconsistent. 
Hypervisor as well is not explained anywhere by MSFT, and has no help system to speak of.

I disabled the items named Hypervisor under the "Startup" and "Services" on this computer,
but that does not do what it says.  

I would like to get rid of Hypervisor, so that it no longer crashes my computer, and so that I
can get back to doing my work.  

Is there anyone on Github who can solve this puzzle, with workable commands, and 
thus prove to me that they are not a robot?  I don't mind following complicated
commands or even edit the registry (with prior backup) if you can prove to me that
you know your stuff. Don't bother with a reply if you really know nothing, because
that does not make you better than me.  

Thank you! 
