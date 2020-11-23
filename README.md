# Virtual box
- Allows the running of multiple OS's simultaneously
- Facilitates testing and allows disaster recovery

**Terminology**
- `Host OS` - the physical computer the VM runs on
- `Gues OS` - the OS used on the instance of a VM
- `Virtual Machine` - the special environment that allows the guest OS to run

<br>

# Vagrant

**What is it?**
- It's an open source tool used to build and manage virtual environments
- Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past.
- Vagrant creates VM's then industry-standard provisioning tools such as shell scripts, Chef, or Puppet can automatically install and configure software on the virtual machine.

**Boxes**
- Pre-made boxes are found [here](https://app.vagrantup.com/boxes/search)
- These are pre-loaded vagrant files that create virtual machines. Typically just an OS.

- Common OS's include Ubuntu and Windows
    - `Ubuntu with GUI` (Graphical User Interface) is an OS like Windows or MacOS which contains a UI for ease of use
    - `Ubuntu headless` is just a terminal therefore it's faster, more secure and much lighter

<br>

**Commands**
- `vagrant init` - creates a `Vagrantfile` in the directory you're in
- `vagrant init <box name>` - creates a `Vagrantfile` with the specified box
- `vagrant up` - creates a virtual machine with the info in `Vagrantfile`
- `vagrant destroy` - destroys the entire VM
- `vagrant ssh` - use once machine is running to log into your VM and use commands in terminal on usual computer
- `vagrant reload` = `vagrant halt` then `vagrant up` - use this if you're running a VM and you make changes to your `Vagrantfile` that you want to see

<br>

# Linux

**NGINX**
- Once loaded into an Ubuntu VM, one can install `nginx` with the command `sudo apt install nginx`
- Open-source software for web serving and reverse proxying
- It's faster than Apache and most other web servers

**Linux terminal commands**
- `sudo` - allows you to use commands as "admin"
- `sudo apt update` - allows you to see apps
- `sudo apt install <package>` - will install the specified package

<br>

---
**Used:**
- [Vagrant](https://www.vagrantup.com/intro)