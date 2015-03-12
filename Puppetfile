# This is a Puppetfile, which describes a collection of Puppet modules. For
# format and syntax examples, see one of the following resources:
#
# https://github.com/rodjek/librarian-puppet/blob/master/README.md
# https://github.com/adrienthebo/r10k/blob/master/README.markdown
#
# Brief example:
#
#   mod 'puppetlabs/stdlib', '4.1.0'
#
# The default production environment for the SE Team is just going to pull in
# the current version of our "profile" module from the Forge and whatever
# dependencies it has.

forge "https://forgeapi.puppetlabs.com"

# PL Modules
mod 'puppetlabs/ruby', '0.4.0'
mod 'puppetlabs/java', '1.1.2'
mod 'puppetlabs/git', '0.2.0'
mod 'puppetlabs/dism', '1.1.0'
mod 'puppetlabs/apache', '1.1.1'
mod 'puppetlabs/pe_gem', '0.0.1'
mod 'puppetlabs/vcsrepo', '1.2.0'
mod 'puppetlabs/stdlib', '4.3.2'
mod 'puppetlabs/ntp', '3.2.1'
mod 'puppetlabs/concat', '1.1.2'
mod 'puppetlabs/firewall', '1.2.0'
mod 'puppetlabs/inifile', '1.1.4'
mod 'puppetlabs/mysql', '2.3.1'

# Community Modules

mod 'stahnma/epel', '1.0.0'
mod 'nanliu/staging', '1.0.2'
mod 'elasticsearch/elasticsearch', '0.3.2'


# TSE modules - either maintained under seteam
# or by individual SE's
# mod 'seteam/profile', '0.2.4'
mod 'openssh',
  :git => 'git@github.com:reidmv/puppet-module-openssh.git',
  :ref => '0e10c540f32ca2a803ca056b8da59bd33a505cee'
mod 'nonpriv',
  :git => 'git@github.com:jpadams/nonpriv.git'
mod 'tsefacts',
  :git => 'git@github.com:mrzarquon/tsefacts.git'
mod 'jenkins',
  :git => 'git://github.com/jenkinsci/puppet-jenkins.git',
  :ref => '29421c4a7725a910cc21fb0fc453f5500c6dae0b'
