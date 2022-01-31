Vagrant.configure(2) do |config|
 config.vm.define "HW" do |subconfig|
  config.vm.box = "Cl4pTrap/centos-7-7"
  config.vm.box_version = "1.0"
  subconfig.vm.hostname="vm-1"
  subconfig.vm.network :private_network, ip: "192.168.50.11"
  subconfig.vm.provider "virtualbox" do |vb|
  vb.memory = "1024"
  vb.cpus = "2"
  subconfig.vm.synced_folder ".", "/vagrant", disabled: true
  end
 end

end
