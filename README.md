# L2TPWin10VPNCreator
Simple CMD script to create L2TP VPN connection with pre-shared key. Once configured, will allow you to create VPN for all users in one click. 

Batch script requires the following to be configured by the user prior to running .bat file:
-L2TP pre-shared key
-Name of the VPN connection
-Server Address of the VPN server

Optional settings include:
-Remember credentials
-Split tunneling

CMD intializes elevated PowerShell script, which in turn runs another PowerShell script which bypasses the client's execution policy and adds a VPN based on the variables provided by the user.
