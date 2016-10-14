Vagrant.configure(2) do |config|
 config.vm.box = "ubuntu/trusty64"
  config.vm.define "ms1" do |ms1|
   ms1.vm.network "private_network", ip: "192.168.43.10"
   ms1.vm.hostname = "ms1"
 end

 config.vm.define "ms2" do |ms2|
  ms2.vm.network "private_network", ip: "192.168.43.11"
  ms2.vm.hostname = "ms2"
 end
end

