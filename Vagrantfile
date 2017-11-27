Vagrant.configure("2") do |config|
  config.vm.box = "box-cutter/ubuntu1404-docker"

   config.vm.define "consul-server" do |cs|
      cs.vm.hostname = "consul-server"
      cs.vm.network "private_network", ip: "172.20.20.31"
      #cs.vm.provision "shell", path: "provision/setup.consul-server.sh", privileged: false
    end
end
