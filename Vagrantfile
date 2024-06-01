Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |vb|
    vb.name = "my_vm_01"
	vb.memory = 512
	vb.cpus = 1
  end
  
  config.vm.box = "hashicorp/bionic64"
  config.vm.network "public_network", bridge: "Ethernet" #REDE Local
end
