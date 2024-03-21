Vagrant.configure("2") do |config|
  config.vm.define "devops" do |devops|
    devops.vm.provider "virtualbox" do |vb_devops|
      vb_devops.memory = 8192
      vb_devops.cpus = 2
    end

    devops.vm.box = "ubuntu/focal64"
    devops.vm.hostname = "devops"
    devops.vm.network "private_network", ip: "10.32.4.139"

  end

  config.vm.define "prometheus" do |prometheus|
    prometheus.vm.provider "virtualbox" do |vb_prometheus|
      vb_prometheus.memory = 8192
      vb_prometheus.cpus = 2
    end

    prometheus.vm.box = "ubuntu/focal64"
    prometheus.vm.hostname = "prometheus"
    prometheus.vm.network "private_network", ip: "10.32.4.178"

  end

  config.vm.define "server1" do |server1|
    server1.vm.provider "virtualbox" do |vb_server1|
      vb_server1.memory = 8192
      vb_server1.cpus = 2
    end

    server1.vm.box = "ubuntu/focal64"
    server1.vm.hostname = "server1"
    server1.vm.network "private_network", ip: "10.32.4.122"

  end

  config.vm.define "server2" do |server2|
    server2.vm.provider "virtualbox" do |vb_server2|
      vb_server2.memory = 8192
      vb_server2.cpus = 2
    end

    server2.vm.box = "ubuntu/focal64"
    server2.vm.hostname = "server2"
    server2.vm.network "private_network", ip: "10.32.4.127"

  end

end