Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/wily64"
  config.vm.provision :ansible_local do |ansible|
    ansible.playbook = "vagrant.yml"
  end
end
