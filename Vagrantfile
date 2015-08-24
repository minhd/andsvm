# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.box = "minhd/andsvm"
  config.vm.network "private_network", ip: "192.168.33.10"

  # Manual box checking `vagrant box outdated`
  # config.vm.box_check_update = false
  # config.vm.network "forwarded_port", guest: 80, host: 8080
  # config.vm.network "public_network"
  # config.vm.synced_folder "../data", "/vagrant_data"

  # naming
  config.vm.define "andsvm" do |andsvm|
  end
  config.vm.provider :virtualbox do |vb|
    vb.name = "andsvm"
  end

end
