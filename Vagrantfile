# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/bionic64"
  config.vm.network "private_network", ip: "192.168.10.2"
  # This creates a webpage on the ip address using your server
  
  # Search how to add a host that will allow one to go to a normal link
  # eg instead of <ipaddress> type in www.development.local to go to the same page 
  # This uses the hosts-updater plugin
  config.vm.hostname =  "www.development.local"
  
end
