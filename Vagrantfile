# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

# ==================================================================================================
# __________                      __                   __    __________ .__                     
# \______   \_______   ____      |__|  ____    ____  _/  |_  \______   \|  |__    ____  _____   
#  |     ___/\_  __ \ /  _ \     |  |_/ __ \ _/ ___\ \   __\  |       _/|  |  \ _/ __ \ \__  \  
#  |    |     |  | \/(  <_> )    |  |\  ___/ \  \___  |  |    |    |   \|   Y  \\  ___/  / __ \_
#  |____|     |__|    \____/ /\__|  | \___  > \___  > |__|    |____|_  /|___|  / \___  >(____  /
#                            \______|     \/      \/                 \/      \/      \/      \/ 
#
# ==================================================================================================
#
# Project Rhea Vagrant Box v0.1.1.2. Generated in 2020.
# This box and everything included comes with ABSOLUTELY NO WARRANTY. use at your own risk.
# The programs included with the Debian GNU/Linux system are free software; the exact distribution terms
# for each program are described in the individual files in /usr/share/doc/*/copyright.

# For help and/or for any feedback, please visit the github page.
# https://github.com/vishvega/Project-Rhea
#
# ==================================================================================================

  config.vm.box = "vishvega/project-rhea"
  config.vm.box_version = "0.1.1"
  config.vm.network "private_network", ip: "192.168.69.96"
  config.vm.synced_folder ".", "/var/www", :mount_options => ["dmode=777", "fmode=666"]

end
