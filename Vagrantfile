Vagrant.configure("2") do |config|
    
    config.vm.define "node01" do |node01|

      node01.vm.box = "centos/7"

      node01.vm.network "private_network", ip: "192.168.33.20"
      node01.vm.hostname = "node01"

      node01.vm.provider "virtualbox" do |vb|
         vb.gui = false
         vb.memory = "2048"
      end
    end
    
end



