#
# vim: set ft=ruby:
#

chef_api "https://chefdev.mkd2.ktc", node_name: "cookbook", client_key: ".cookbook.pem"

site :opscode

metadata

cookbook 'ktc-etcd'
cookbook 'ktc-galera', path: 'test/integration/cookbooks/ktc-galera'
cookbook 'ktc-testing'
