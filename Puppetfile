# Puppet modules needed for local environment
# basemodules is provided by ci-images/puppet6-master-base

# Test plain GitHub over HTTP
mod 'apache',
  :git => 'https://github.com/puppetlabs/puppetlabs-apache.git',
  :tag => 'v8.6.0'

# Test GitHub w/ git-tags (github-tags perhaps?)
mod 'docker',
  :git => 'git@github.com:puppetlabs/puppetlabs-docker.git',
  :tag => 'v6.1.0'

# Test regular git-tags against non-GitHub
mod 'logrotate',
  :git => 'git@gitlab.com:hitchhikers/puppet-modules/voxpupuli-logrotate.git',
  :tag => 'v6.0.0'

# Test regular HTTP against GitLab
mod 'lvm',
  :git => 'https://gitlab.com/hitchhikers/puppet-modules/puppetlabs-lvm.git',
  :tag => 'v1.4.0'

# External repo - sr.ht
mod 'rabbitmq',
  :git => 'https://git.sr.ht/~mindtooth/puppet-rabbitmq',
  :tag => 'v13.0.0'
