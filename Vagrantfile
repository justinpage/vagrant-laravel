# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
	config.vm.box = "ubuntu_14.04x64"

	config.vm.network "forwarded_port", guest: 80, host: 8080

	config.vm.provision :shell, :path => "install.sh"
end
