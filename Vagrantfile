Vagrant.configure(2) do |config|

 config.vm.define "docker" do |docker|
   docker.vm.box = "centos/7"
   docker.vm.hostname = "docker"
   docker.vm.network "private_network",ip:"10.50.1.10"
   config.vm.synced_folder ".","/vagrant",disabled:true
 end
end
