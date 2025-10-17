Vagrant.configure("2") do |config|
  config.vm.box = "debian/bookworm64"
  config.ssh.insert_key = false

  config.vm.define "web" do |web|
    web.vm.hostname = "web"
    web.vm.network :private_network, ip: "192.168.57.10"
  end
end
