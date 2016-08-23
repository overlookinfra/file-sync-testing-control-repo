# A Puppetfile for a control repo that represents a more realistic deployment base



# Customers may have a security policies that prevent direct access to
# the internet, do not assume forge access, though to bootstrap this
# we will use Github as our "internal mirror"
forge "http://forge.puppetlabs.com"


# Additional modules to complement and complete a PE installation
# The all_envs.tgz should contain:
# 'hunner/hiera', 'puppetlabs/puppetserver_gem', 'puppetlabs/inifile',
# 'puppetlabs/concat', 'puppetlabs/hocon', 'puppetlabs/stdlib',
# 'puppetlabs/vcsrepo', 'puppet/archive',
mod 'npwalker/pe_code_manager_webhook', git: 'https://github.com/npwalker/pe_code_manager_webhook',       tag: '1.0.7'


# Basic linux host management
mod 'puppetlabs/accounts',  git: 'https://github.com/puppetlabs/puppetlabs-accounts',  tag: '1.0.0'
mod 'puppetlabs/apt',       git: 'https://github.com/puppetlabs/puppetlabs-apt',       tag: '2.2.2'
mod 'jlambert121/yum',      git: 'https://github.com/jlambert121/jlambert121-yum',     tag: '0.2.1'
mod 'puppetlabs/ntp',       git: 'https://github.com/puppetlabs/puppetlabs-ntp',       tag: '4.2.0'
mod 'puppetlabs/firewall',  git: 'https://github.com/puppetlabs/puppetlabs-firewall',  tag: '1.8.1'
mod 'puppetlabs/motd',      git: 'https://github.com/puppetlabs/puppetlabs-motd',      tag: '1.4.0'
mod 'yo61/logrotate',       git: 'https://github.com/yo61/puppet-logrotate',           tag: 'v1.4.0'
mod 'ghoneycutt/ssh',       git: 'https://github.com/ghoneycutt/puppet-module-ssh',    tag: 'v3.36.0'
mod 'ghoneycutt/pam',       git: 'https://github.com/ghoneycutt/puppet-module-pam',    tag: 'v2.22.0'
mod 'saz/rsyslog',          git: 'https://github.com/saz/puppet-rsyslog',              tag: 'v3.5.1'

