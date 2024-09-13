# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|

  config.vm.box = "cybridtechnology-labs/cybrid-vagrant-lab"

  config.vm.provider "virtualbox" do |vb|
    
	# Virtualbox settings
	
	# Display the VirtualBox GUI when booting the machine
	vb.gui = true
	
	# Change the disk size
	vb.disksize.size = '25GB'
	
	# Customize the name
	vb.name = "cybrid-lab-ubuntu"
	
	# Change the amount of memory
	vb.memory = "2048"
	
	# Change the amount of virtual CPUs
	vb.cpus = "2"
	
	# Disable serial ports
	vb.customize [ "modifyvm", :id, "--uart1", "off" ]
	vb.customize [ "modifyvm", :id, "--uart2", "off" ]
	vb.customize [ "modifyvm", :id, "--uart3", "off" ]
	vb.customize [ "modifyvm", :id, "--uart4", "off" ]
  end

end
