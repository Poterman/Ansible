Vagrant.configure("2") do |config|
    config.vm.define "web" do |web|
        web.vm.box="centos/7"
        web.vm.network "private_network", ip: "10.0.200.101"
        web.vm.hostname="web"
    end
    
    config.vm.define "db" do |db|
        db.vm.box="centos/7"
        db.vm.network "private_network", ip: "10.0.200.102"
        db.vm.hostname="db"
    end
    
    config.vm.define "ans" do |ans|
        ans.vm.box="centos/7"
        ans.vm.network "private_network", ip: "10.0.200.10"
        ans.vm.hostname="provision"
    end
end
