Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  # Puppet
  config.vm.provision "puppet" do |puppet|
    puppet.manifests_path = "manifests"
    puppet.manifest_file = "default.pp"
    puppet.options = "--verbose --debug"
  end
end