Vagrant.configure("2") do |config|
  config.vm.provision "shell", inline: "echo Hello"

  config.vm.define "mockwebserver" do |mockwebserver|
    mockwebserver.vm.box = "hashicorp/precise32"
  end
end
