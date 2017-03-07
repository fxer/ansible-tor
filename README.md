## Ansible Role: Tor relay
Configure a Tor relay on a RedHat/CentOS 7 server

## Tasks
* Install latest Tor package from EPEL
* Configure SELinux to permit Tor via `tor_can_network_relay`
* Create `torrc` config from template

See [defaults/main.yml](defaults/main.yml) for `torrc` configuration options

## License
2-clause BSD
