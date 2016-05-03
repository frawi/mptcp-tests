# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|
  config.vm.box = "comnets/mininet-mptcp"

  # this is useful because we might want to use xterms in mininet
  config.ssh.forward_x11 = true

  config.vm.provider "virtualbox" do |vb|
    # Enable I/O APIC to use multiple CPUs
    #vb.customize ["modifyvm", :id, "--ioapic", "on"]
    #vb.cpus = 2
  
    # Customize the amount of memory on the VM:
    #vb.memory = "4096"
  end
end
