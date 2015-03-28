# Panamax_Hanlon
Panamax Hanlon template with all components of Hanlon namely Server, iPXE, tftp, client etc..

Thanks to Tom Mcsweeney for all the support and help to get the understanding of Hanlon, besides being the author of 'Hanlon' - a bare metal provisioning tool

Thanks to Joseph callen for patiently helping me to install hanlon on Fedora21 - during 1st time

Here is what this Panamax template is doing

tl;dr
It will help deploy  and run the Hanlon in a single click on any chosen cloud or in your Mac (if you have installed the pre-requisites)

===
Prerequisites
  - install Vagrant
  - install virtual box
  - install Panamax.io (a simple brew install)
  
running Hanlon
 - Check for the template by name Panamax_Hanlon 
 - the template has all the components of Hanlon
 - Choose your cloud to deploy or use your local Mac (you can do the same in Linux as well, as there is a panamax for linux)
 - run and try provisioning a VM or a physical machine with chosen OS
 - For Hanlon features and usage look for https://github.com/csc/Hanlon
 
updates on Hanlon
Every new updates to Hanlon will bee-line to Dockerhub as containers and will be periodically updating this template or will update with appropriate description for the new panamax_hanlon template


Tracert on here is how and why!!

- I was looking for a Vagrant driven control on the life cycle of *inx.
- I was looking for docker combination
- CoreOS and fleet was more than a boon to add to this
- running on a Mac directly without heavy duty VMs for provisioning
- Ultimately to run Hanlon and get a hand on it

Panamax was a super close hit and I found using Vagrant Spinning a CoreOS having a fleet on top running docker and connected to dockerhub and helps stictch multiple containers in either Mac or any cloud.. so there.





 
