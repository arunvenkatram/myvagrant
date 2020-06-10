# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.define "dockermaster" do |dockermaster|
  dockermaster.vm.box = "ubuntu/xenial64"
  dockermaster.vm.hostname = 'docker.master'
  dockermaster.vm.network :private_network, ip: "192.168.10.10"
  config.vm.provider "virtualbox" do |v|
  	v.memory = 4096
	v.cpus = 4
  end
  end

  config.vm.define "server1" do |server1|
  server1.vm.box = "geerlingguy/centos7"
  server1.vm.hostname = 'server1'
  server1.vm.network :private_network, ip: "192.168.10.20"
  config.vm.provider "virtualbox" do |w|
    w.memory = 1024
  end
  end

  config.vm.define "client1" do |client1|
  client1.vm.box = "geerlingguy/centos7"
  client1.vm.hostname = 'client1'
  client1.vm.network :private_network, ip: "192.168.10.30"
  config.vm.provider "virtualbox" do |x|
    x.memory = 1024
  end
  end
  config.vm.define "client2" do |client2|
  client2.vm.box = "geerlingguy/centos7"
  client2.vm.hostname = 'client2'
  client2.vm.network :private_network, ip: "192.168.10.35"
  config.vm.provider "virtualbox" do |x|
    x.memory = 1024
  end
  end
  config.vm.define "dockernode" do |dockernode|
  dockernode.vm.box = "ubuntu/xenial64"
  dockernode.vm.hostname = 'docker.node'
  dockernode.vm.network :private_network, ip: "192.168.10.40"
  config.vm.provider "virtualbox" do |y|
    y.memory = 4096
  end
  end
 # config.vm.provision "shell", inline: 'sudo cp /vagrant/hosts /etc/hosts'
  config.vm.define "nagios" do |nagios|
  nagios.vm.box = "geerlingguy/centos7"
  nagios.vm.hostname = 'nagios'
  nagios.vm.network :private_network, ip: "192.168.10.60"
  config.vm.provider "virtualbox" do |d|
  	d.memory = 4096
  end
  end
  config.vm.define "ubuntu" do |ubuntu|
  ubuntu.vm.box = "wesmcclure/ubuntu1404-docker"
  ubuntu.vm.hostname = 'ubuntu.client'
  ubuntu.vm.network :private_network, ip: "192.168.10.70"
  config.vm.provider "virtualbox" do |e|
  	e.memory = 1024
  end
  end
  config.vm.define "kubenode" do |kubenode|
  kubenode.vm.box = "geerlingguy/centos7"
  kubenode.vm.hostname = 'kubenode'
  kubenode.vm.network :private_network, ip: "192.168.10.80"
  config.vm.provider "virtualbox" do |v|
  	v.memory = 8192
	v.cpus = 4
  end
  end
  config.vm.define "ansibletower" do |ansibletower|
  ansibletower.vm.box = "ansible/tower"
  ansibletower.vm.hostname = 'ansible.local.com'
  ansibletower.vm.network :private_network, ip: "192.168.10.90"
  config.vm.provider "virtualbox" do |v|
  	v.memory = 2560
	v.cpus = 3
  end
  end
  config.vm.define "devstack" do |devstack|
  devstack.vm.box = "ubuntu/xenial64"
  devstack.vm.hostname = 'devstack'
  devstack.vm.network :private_network, ip: "192.168.10.100"
  config.vm.provider "virtualbox" do |x|
  	x.memory = 8192
	x.cpus = 4
  end
  end
  config.vm.define "kubemaster" do |kubemaster|
  kubemaster.vm.box = "geerlingguy/centos7"
  kubemaster.vm.hostname = 'kubemaster'
  kubemaster.vm.network :private_network, ip: "192.168.10.110"
  config.vm.provider "virtualbox" do |x|
  	x.memory = 4096
	x.cpus = 2
  end
  end
  config.vm.define "jenkinsserver" do |jenkinsserver|
  jenkinsserver.vm.box = "geerlingguy/centos7"
  jenkinsserver.vm.hostname = 'jenkinsserver.local.com'
  jenkinsserver.vm.network :private_network, ip: "192.168.10.120"
  config.vm.provider "virtualbox" do |x|
  	x.memory = 4096
	x.cpus = 4
  end
  end
  config.vm.define "kali" do |kali|
  kali.vm.box = "Sliim/kali-linux-2.0-amd64"
  kali.vm.hostname = 'kali.local.com'
  kali.vm.network :private_network, ip: "192.168.10.130"
  config.vm.provider "virtualbox" do |x|
  	x.memory = 8192
	x.cpus = 4
  end
  end
end
#jc  skdv skdfvnksdf vkdn fvkla dklj lsdfv
#ksc kvndkfv kdfb
