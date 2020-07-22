Vagrant.configure("2") do |config|

    config.vm.box = "ubuntu/trusty64"

    config.vm.provider "virtualbox" do |v|
        v.memory = 1024
    end

    config.vm.define "wordpress" do |wp|
        wp.vm.network "public_network", ip: "192.168.X.50"
    end

    config.vm.define "mysql" do |sql|
        sql.vm.network "public_network", ip: "192.168.X.51"
    end
end