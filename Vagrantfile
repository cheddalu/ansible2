# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.

Vagrant.configure(2) do |config|

 config.vm.define "control" do |control|
    control.vm.box = "ubuntu/xenial64"
    control.vm.hostname = "control"
    control.vm.network "private_network", ip: "192.168.33.100"
 end

end
