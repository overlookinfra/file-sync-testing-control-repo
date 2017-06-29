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


# Advanced linux host management
mod 'garethr/docker', git: 'https://github.com/garethr/garethr-docker', tag: 'v5.2.0'
mod 'vshn/gitlab',    git: 'https://github.com/vshn/puppet-gitlab',     tag: 'v1.8.0'
mod 'gms',            git: 'https://github.com/abrader/abrader-gms',    tag: 'v1.0.2'



# Common tools in an infrastructure
mod 'puppetlabs/postgresql',       git: 'https://github.com/puppetlabs/puppetlabs-postgresql', tag: '4.7.1'
mod 'camptocamp/openldap',         git: 'https://github.com/camptocamp/puppet-openldap',       tag: '1.14.0'
mod 'arioch/redis',                git: 'https://github.com/arioch/puppet-redis',              tag: '1.2.2'
mod 'golja/influxdb',              git: 'https://github.com/n1tr0g/golja-influxdb',            tag: '3.0.1'
mod 'saz/memcached',               git: 'https://github.com/saz/puppet-memcached',             tag: 'v2.8.1'

mod 'thais/squid3',          git: 'https://github.com/thias/puppet-squid3',              tag: '1.0.0'
mod 'puppetlabs/haproxy',    git: 'https://github.com/puppetlabs/puppetlabs-haproxy',    tag: '1.4.0'
mod 'puppetlabs/apache',     git: 'https://github.com/puppetlabs/puppetlabs-apache',     tag: '1.10.0'
mod 'jfryman/nginx',         git: 'http://github.com/jfryman/puppet-nginx',              tag: 'v0.3.0'
mod 'puppetlabs/tomcat',     git: 'https://github.com/puppetlabs/puppetlabs-tomcat',     tag: '1.5.0'

mod 'rtyler/jenkins',        git: 'https://github.com/jenkinsci/puppet-jenkins',         tag: 'v1.6.1'
mod 'sensu/sensu',           git: 'https://github.com/sensu/sensu-puppet',               tag: 'v2.1.0'
mod 'bfraser/grafana',       git: 'https://github.com/bfraser/puppet-grafana',           tag: 'v2.5.0'

mod 'elasticsearch/elasticsearch',     git: 'https://github.com/elastic/puppet-elasticsearch',     tag: '0.11.0'
mod 'elasticsearch/logstash',          git: 'https://github.com/elastic/puppet-logstash',          tag: '0.6.4'
mod 'elasticsearch/logstashforwarder', git: 'https://github.com/elastic/puppet-logstashforwarder', tag: '0.1.1'

mod 'puppetlabs/java',       git: 'https://github.com/puppetlabs/puppetlabs-java',       tag: '1.5.0'
mod 'puppetlabs/java_ks',    git: 'https://github.com/puppetlabs/puppetlabs-java_ks',    tag: '1.4.1'

