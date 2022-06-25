Vagrant.configure("2") do |config|
    config.vm.box = "amd64"
    config.vm.provider "virtualbox" do |v|
        v.memory = 2048
        v.cpus = 2
    end
    config.vm.provision "bootstrap", type: "shell" do |s|
        s.inline = "sudo apt install ntp -y;"
        s.inline = "sudo apt install nginx -y;"
    end
    config.vm.network "forwarded_port", guest: 80, host: 8080
end