From http://docs.puppetlabs.com/guides/installation.html#post-install

This assumes puppet run in standalone mode.

1a. Update package repository.
1b. Install puppet-common via package manager.

2. Default puppet dir for manifests, etc, under /etc/puppet/
Settings for standalone puppet nodes should go in the [main] block of /etc/puppet/puppet.conf

3. Enable
You can start and permanently enable these services using Puppet:

$ sudo puppet resource service puppet ensure=running enable=true

 

