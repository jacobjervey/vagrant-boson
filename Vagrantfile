Vagrant::Config.run do |config|

  config.vm.box = "ubuntuprecise32"
  config.vm.provision :chef_solo do |chef|
  	chef.cookbooks_path = "boson-cookbooks"
  	chef.add_recipe 'boson::init'
  end

end
