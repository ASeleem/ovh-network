# ovh-network
<br />
<p>Configuring Network Bridging OVH for CentOS 7.x </p>
<br />
We will configure Network Bridging by few steps : 
<br />
1 - Download this ISO file from here : http://aseleem.com/projects/OVH-Network.iso
<br />
2 - Import this ISO file to your VM
<br />
3 - Excute this command : mkdir /OVH_NB mount -t auto -r /dev/cdrom /OVH_NB && cd /OVH_NB && ./network.sh
<br />
4 - The script will ask you some questions such as 
<br />
  Interface Name ( ex : eth0 )
 <br />
  IP
 <br />
  MAC
 <br />
  GATEWAY ( which is the main IP of your server where you replace the last octet by 254 )
 <br />
  Network GATEWAY ( which is the main IP of your server where you replace the last octet by 0 )
 <br /><br />
 
 
 ... Done ;) 
