Tenant-Isolation Exercises
===============================================  
----
These exercises are intended to provide clarification on the various methods one can utilize to perform tenant-network isolation inside infrastructure-as-a-service platforms like OpenStack.

Requirements
--------------  

  - Ubuntu
  - 3 nodes on same subnet (ex. 192.168.56.56-58/24)
  - apt-get install vlan bridge-utils tcpdump

Resources: [iproute2 cheatsheet] & [ietf vlan doc] & [ietf vxlan doc] 

[iproute2 cheatsheet]:http://baturin.org/docs/iproute2/
[ietf vlan doc]:http://tools.ietf.org/html/rfc5517
[ietf vxlan doc]:http://tools.ietf.org/html/draft-mahalingam-dutt-dcops-vxlan-00
