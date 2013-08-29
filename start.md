### How to start Vagrant machine (first time):
0 - (ruby is required, rvm is recommended: https://rvm.io/rvm/install)
0 - (get latest vagrant: http://downloads.vagrantup.com/)

Then...

1 - $ vagrant plugin bundle
2 - $ vagrant up

### Normal -daily- usage:
$ vagrant up 		# start the configured machine
$ vagrant halt 		# shutdown the machine
$ vagrant ssh		# get into the machine
$ vagrant destroy	# destroy current machine
