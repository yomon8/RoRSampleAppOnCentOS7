# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "centos/7"
  config.vm.hostname = "RoR4App"
  config.vm.network "private_network", ip: "192.168.33.11"

  config.vm.provision "ansible" do |ansible|
        ansible.playbook = "deploy_ror.yml"
  end
end
