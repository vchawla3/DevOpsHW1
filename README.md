# DevOpsHW1
Using ansible, automatically configure a headless ubuntu 16.04 server running VirtualBox, with phpVirtualBox, and vagrant.

## Files in Repo
Configure.yml provisions xenial ubuntu 16.04 remote host with virtualbox, phpVirtualbox, and vagrant

provisionVagrantVM.yml destroys any running vagrant vm, makes sure Vagrantfile is absent, then inits a vm, edits the vagrant file with necessary edits to make it work on this remote host, and runs vagrant up.

## Screencast
[Link to screencast](https://youtu.be/h6K7sNhbY2g "vchawla3's screencast")
