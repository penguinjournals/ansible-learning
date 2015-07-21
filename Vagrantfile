# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.network :private_network, ip: "10.0.0.2"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "site.yml"
  end
end
