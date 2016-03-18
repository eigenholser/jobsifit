# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  # Every Vagrant virtual environment requires a box to build off of.
  config.vm.box = "jobsifit"
  config.vm.box_url = "#{ENV['VAGRANT_BOXES_URL']}/jobsifit.box"

  # Override default
  config.vm.network "forwarded_port", guest: 8000, host: 8000
  config.vm.network "forwarded_port", guest: 3306, host: 3306
  config.vm.network "forwarded_port", guest: 3333, host: 3333
  config.vm.network "forwarded_port", guest: 9485, host: 9485
end
