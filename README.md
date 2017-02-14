# ovh-network
Configuring Network Bridging OVH for CentOS 7.x
We will configure Network Bridging by few steps : 
1 - Download this ISO file from here : http://aseleem.com/projects/OVH-Network.iso
2 - Import this ISO file to your VM
3 - Excute this command : mkdir /OVH_NB mount -t auto -r /dev/cdrom /OVH_NB && cd /OVH_NB && ./network.sh
4 - The script will ask you some questions such as 
  Interface Name ( ex : eth0 )
  IP
  MAC
  GATEWAY ( which is the main IP of your server where you replace the last octet by 254 )
  Network GATEWAY ( which is the main IP of your server where you replace the last octet by 0 )
 
 
 ... Done ;) 
