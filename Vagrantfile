# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|
 config.vm.box = "ubuntu/xenial64"
 config.vm.box_version = "20190208.0.0"
 config.vm.provider "virtualbox" do |vb|
     vb.customize [ "modifyvm", :id, "--uartmode1", "disconnected" ]
  end
 config.vm.network "private_network", ip: "192.168.33.10"
end
