# GRAAD
CSC GRAAD КСК ГРААД (комплексная система контроля 2010-2015 гг., микропрограмма GRAAD 2008-2010 гг.)

Прошивка: AXIS, ASUS. АППАРАТНО МОДИФИЦИРОВАННЫЙ WI-FI РОУТЕР ASUS WL-500 GP V2.


<a href="https://cscgraad.blogspot.com/p/monocle.html" style="background-color: white; font-size: medium; font-weight: 400;"><img border="0" data-original-height="900" data-original-width="900" height="650" src="https://raw.githubusercontent.com/EMIIA/GRAAD/master/GRAAD1080.png" style="font-family: &quot;times new roman&quot;;" width="640" /></a>


SNMP: uptime values no longer depends on the system time
UPnP: it's now possible to select interface for which interface address reported back to clients (IP Config - Misc), port-forwards are working just like other virtual servers
UPnP: additionally protected by built-in firewall in case when multicast forwards enabled
IPTV: added udpxy (check IP Config - Miscellaneous: IPTV UDP Multicast to HTTP Proxy Port) to enable-disable it
Added Get IP automatically option to the WAN & LAN page
DHCP: added support for some broken DHCP servers (e.g. Golden Telecom)
Manual DNS server entries are no longer added to routing table
Fixed Redirects in the web-iface (it should no longer redirect to internal address);
Enabled Idle Disconnect functionality for PPPoE/PPTP. It's recomended to turn this feature off by typing zero in this field.
L2TP speed increase (up to 2.5 times compared to previous versions) and correct tunnel termination
PPTP sync option is now correctly handled and enabled by default, improved overall stability, cleared up logs;
Updated QuickSetup to recent PPPoE, PPTP and L2TP changes
Added fine grained WPA control on the Wireless page: added separate WPA Enterprise, WPA2 Enterprise, WPA Personal, WPA2 Personal and WPA-Auto-Personal (which is wpa-psk + wpa2-psk for TKIP+AES, wpa-psk for TKIP and wpa2-psk for AES).
Added Regulatory Mode field (802.11d/802.11h/off) to the Wireless - Advanced page. This should fix some problems with Intel WiFi cards (select 802.11d mode).
Virtual Servers has now separate default action in the WAN to LAN firewall.
Added Host Name field to the Manual DHCP MAC list.
Added Comment field to Wireless - Access list.
FTP: switched to vsftpd, reworked web-iface.
Samba: extended web-iface, new share modes - all partitions, manual share list.
Samba: Windows Vista support, W2K3SP1 compatibility
Added utf8 as default encoding of the hard/flash drive (enabled by default).
NFS: fixed some /etc/exports problems
Kernel modules are now stored in single directory
Added ftdi_sio usb to serial converter module.
USB updates
VLAN support fixes, updated robocfg
Added Enable USB Storage selection to the System Setup - Services page to enable usb storage modules to load automatically
Added filesystem type autodetection to automount portition





<a href="https://cscgraad.blogspot.com/p/monocle.html" style="background-color: white; font-size: medium; font-weight: 400;"><img border="0" data-original-height="900" data-original-width="1600" height="320" src="https://raw.githubusercontent.com/EMIIA/GRAAD/master/axisasus.png" style="font-family: &quot;times new roman&quot;;" width="640" /></a>


