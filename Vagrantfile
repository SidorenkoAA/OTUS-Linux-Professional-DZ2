# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
   config.vm.box = "ubuntu-server-22_04"
   config.vm.box_check_update = false
   config.vm.hostname = "kernel-update"
   config.vm.define "kernel-update"
   config.vm.provider "virtualbox" do |vb|
     vb.memory = "2048"
     vb.cpus = "2"
   end
end
