# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.network :public_network
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "site.yml"
  end
end
