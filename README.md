# L2TPWin10VPNCreator
Simple batch script to create L2TP VPN connection with pre-shared key on Windows 10. Once configured, will allow you to create VPN for all users in one click. 

Batch script requires the following to be configured by the user prior to running .bat file:
<br>-L2TP pre-shared key
<br>-Name of the VPN connection
<br>-Server Address of the VPN server

Optional settings include:
<br>-Remember credentials
<br>-Split tunneling

Batch script intializes elevated PowerShell script, which in turn runs another PowerShell script which bypasses the client's execution policy and adds a VPN based on the variables provided by the user.
