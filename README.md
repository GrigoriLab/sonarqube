sudo sysctl -w vm.max_map_count=262144
or set vm.max_map_count in /etc/sysctl.conf and reload the parameter with sysctl -p
