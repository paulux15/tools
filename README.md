# tools
Tools used mainly for SW Development onto Linux

*******
Tables of contents:

1. [List of Tools](#list)
2. [NET Tool](#tool-net)
3. [STB Tool](#tool-stb)

*******

<!---
___________________________________________________________________________
--->

<div id=`list`/>

# List of Tools


<!---
___________________________________________________________________________
--->

<div id=`tool-net`/>

# Nework Tool

```
$> ./MY-NET-Show_ARP_Table.sh
```


<!---
___________________________________________________________________________
--->

<div id=`tool-stb`/>

# STB Tool

```
$> ./MY-STB_Network_with_NAT.sh
Script must be run with sudo.

$> sudo  ./MY-STB_Network_with_NAT.sh
Usage: ./MY-STB_Network_with_NAT.sh   <status|nat|tftpd|nfs|dnsmasq>
     status   check status of services (tftpd, nfs, dnsmasq).

        nat   setup Kernel iptables to enable NAT protocol.
      tftpd   enable tftpd-hpa service.
        nfs   enable nfs-kernel-server service.
    dnsmasq   enable dnsmasq service.
```
