Vagrant.configure("2") do |config|
 
  config.vm.box = "centos/7"

  
  config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.provision "shell", inline: path: "provision.sh"

end
