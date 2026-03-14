# tp3-vlan

separer le reseau avec un switch

j ai mis 2 pc sur un switch

pc rh
ip 192.168.10.10
mask 255.255.255.0

pc it
ip 192.168.20.10
mask 255.255.255.0

sur le switch jai cree vlan 10 rh
et vlan 20 IT

port fa0 1 dans vlan 10
port fa0 2 dans vlan 20

test ping 192.168.20.10

ca marche pas normal
car vlan different
il faut un routeur pour communiquer

tp fait sur packet tracer
