# -*- mode: ruby -*-
# vi: set ft=ruby :

API_VERSION   = "2"
#DOMAIN        = "nip.io"
PRIVATE_KEY   = "~/.ssh/id_rsa"
PUBLIC_KEY    = "~/.ssh/id_rsa.pub"
CENTOS_IP1    = "192.168.56.3"
CENTOS_IP2    = "192.168.56.4"
CENTOS_IP3    = "192.168.56.5"
CENTOS_IP4    = "192.168.56.6"
CENTOS_IP5    = "192.168.56.7"
CENTOS_IP6    = "192.168.56.8"
CENTOS_IP7    = "192.168.56.9"
CENTOS_IP8    = "192.168.56.10"
CENTOS_BOX    = "generic/rhel8"

#Vagrant.configure("2") do |config|
#  config.vm.box = "generic/rhel8"
#end
#vagrant init alvistack/centos-7

#vagrant up


Vagrant.configure(API_VERSION) do |config|

  config.vm.define "centos-vm1" do |vm1|
    vm1.vm.box = CENTOS_BOX
    vm1.vm.network "private_network", ip: CENTOS_IP1
    vm1.vm.host_name = CENTOS_IP1 # + '.' + DOMAIN
    vm1.ssh.insert_key = false
    vm1.ssh.private_key_path = [PRIVATE_KEY, "~/.vagrant.d/insecure_private_key"]
    vm1.vm.provision "file", source: PUBLIC_KEY, destination: "~/.ssh/authorized_keys"

    vm1.vm.provider "virtualbox" do |v|
      v.memory = "1024"
      v.cpus = "1"
    end

  end

  config.vm.define "centos-vm2" do |vm2|
    vm2.vm.box = CENTOS_BOX
    vm2.vm.network "private_network", ip: CENTOS_IP2
    vm2.vm.host_name = CENTOS_IP2 #+ '.' + DOMAIN
    vm2.ssh.insert_key = false
    vm2.ssh.private_key_path = [PRIVATE_KEY, "~/.vagrant.d/insecure_private_key"]
    vm2.vm.provision "file", source: PUBLIC_KEY, destination: "~/.ssh/authorized_keys"

    vm2.vm.provider "virtualbox" do |v|
      v.memory = "1024"
      v.cpus = "1"
    end
  
  end

  config.vm.define "centos-vm3" do |vm3|
    vm3.vm.box = CENTOS_BOX
    vm3.vm.network "private_network", ip: CENTOS_IP3
    vm3.vm.host_name = CENTOS_IP3 #+ '.' + DOMAIN
    vm3.ssh.insert_key = false
    vm3.ssh.private_key_path = [PRIVATE_KEY, "~/.vagrant.d/insecure_private_key"]
    vm3.vm.provision "file", source: PUBLIC_KEY, destination: "~/.ssh/authorized_keys"

    vm3.vm.provider "virtualbox" do |v|
      v.memory = "1024"
      v.cpus = "1"
    end

  end

  config.vm.define "centos-vm4" do |vm4|
    vm4.vm.box = CENTOS_BOX
    vm4.vm.network "private_network", ip: CENTOS_IP4
    vm4.vm.host_name = CENTOS_IP4 #+ '.' + DOMAIN
    vm4.ssh.insert_key = false
    vm4.ssh.private_key_path = [PRIVATE_KEY, "~/.vagrant.d/insecure_private_key"]
    vm4.vm.provision "file", source: PUBLIC_KEY, destination: "~/.ssh/authorized_keys"

    vm4.vm.provider "virtualbox" do |v|
      v.memory = "1024"
      v.cpus = "1"
    end

  end

  config.vm.define "centos-vm5" do |vm5|
    vm5.vm.box = CENTOS_BOX
    vm5.vm.network "private_network", ip: CENTOS_IP5
    vm5.vm.host_name = CENTOS_IP5 #+ '.' + DOMAIN
    vm5.ssh.insert_key = false
    vm5.ssh.private_key_path = [PRIVATE_KEY, "~/.vagrant.d/insecure_private_key"]
    vm5.vm.provision "file", source: PUBLIC_KEY, destination: "~/.ssh/authorized_keys"

    vm5.vm.provider "virtualbox" do |v|
      v.memory = "1024"
      v.cpus = "1"
    end
  
  end

#  config.vm.define "centos-vm6" do |vm6|
#    vm6.vm.box = CENTOS_BOX
#    vm6.vm.network "private_network", ip: CENTOS_IP6
#    vm6.vm.host_name = CENTOS_IP6 #+ '.' + DOMAIN
#    vm6.ssh.insert_key = false
#    vm6.ssh.private_key_path = [PRIVATE_KEY, "~/.vagrant.d/insecure_private_key"]
#    vm6.vm.provision "file", source: PUBLIC_KEY, destination: "~/.ssh/authorized_keys"

#    vm6.vm.provider "virtualbox" do |v|
#      v.memory = "1024"
#      v.cpus = "1"
#    end

#  end

#  config.vm.define "centos-vm7" do |vm7|
#    vm7.vm.box = CENTOS_BOX
#    vm7.vm.network "private_network", ip: CENTOS_IP7
#    vm7.vm.host_name = CENTOS_IP7 #+ '.' + DOMAIN
#    vm7.ssh.insert_key = false
#    vm7.ssh.private_key_path = [PRIVATE_KEY, "~/.vagrant.d/insecure_private_key"]
#    vm7.vm.provision "file", source: PUBLIC_KEY, destination: "~/.ssh/authorized_keys"

#    vm7.vm.provider "virtualbox" do |v|
#      v.memory = "1024"
#      v.cpus = "1"
#    end

#  end

#  config.vm.define "centos-vm8" do |vm8|
#    vm8.vm.box = CENTOS_BOX
#    vm8.vm.network "private_network", ip: CENTOS_IP8
#    vm8.vm.host_name = CENTOS_IP8 #+ '.' + DOMAIN
#    vm8.ssh.insert_key = false
#    vm8.ssh.private_key_path = [PRIVATE_KEY, "~/.vagrant.d/insecure_private_key"]
#    vm8.vm.provision "file", source: PUBLIC_KEY, destination: "~/.ssh/authorized_keys"

#    vm8.vm.provider "virtualbox" do |v|
#      v.memory = "1024"
#      v.cpus = "1"
#    end

#  end  

end
