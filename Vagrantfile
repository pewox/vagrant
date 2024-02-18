Vagrant.configure("2") do |config|

  config.vm.define "ansible" do |ansible|
    ansible.vm.box = "bento/ubuntu-22.04"
    ansible.vm.hostname = "ansible"
    ansible.vm.network :private_network, ip: "192.168.100.100"
  end
  
  config.vm.define "debian" do |debian|
    debian.vm.box = "generic/debian12"
    debian.vm.hostname = "debian"
    debian.vm.network :private_network, ip: "192.168.100.10"
  end

  config.vm.define "rocky" do |rocky|
    rocky.vm.box = "bento/rockylinux-8"
    rocky.vm.hostname = "rocky"
    rocky.vm.network :private_network, ip: "192.168.100.20"
  end
  
  config.vm.define "suse" do |suse|
    suse.vm.box = "generic/opensuse42"
    suse.vm.hostname = "suse"
    suse.vm.network :private_network, ip: "192.168.100.30"
  end
end
