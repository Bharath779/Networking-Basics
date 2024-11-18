Subnet (subnetworking):
  Its nothing but dividing the larger N/w into smaller N/w
  i.e Lets Consider 
    IP has 192.64.32.0
    in this IP we require only 255 ips
    so we larger IP_address 192.64.32.0 into samller 192.64.32.0/24
    i.e 192.64.32.0/24
    32-24=8 i.e 2^8 =256 IPs.
    so we got required ips i.e 192.64.32.0 to 192.64.32.255

    Examples of Subnet
    < 172.168.3.0/30
      32-30=2 i.e 2^2 =4 IPs.
      so we got required ips i.e 192.64.32.0 to 192.64.32.3

    < 172.168.3.0/16
      32-30=2 i.e 2^2 =65025 IPs.
      so we got required ips i.e 192.64.0.0 to 192.64.255.255 