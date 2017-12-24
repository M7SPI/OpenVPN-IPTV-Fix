# OpenVPN-IPTV-Fix
A way to setup openvpn server on a vps to work around isp blocks
OpenVPN installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

You will already ready needed to purchase a vps or dedicated server. Try lowendboxes.com for reasonable providers. This can be has little has £3 a month. I wont digress on the best suppliers just check there feedback.

Installation

Run the script and follow the assistant:

wget https://git.io/vbQxJ -O openvpninstall.sh && bash openvpninstall.sh

Once it ends it will save the client.ovpn (or what ever you called the client file you created) file in the root folder. You will need to download this locally then transefer it to your device running the openvpn client, that may be an android client, ios or windows client.

I just downloaded to my laptop, emailed to my my phone to use in android openvpnclient. You could use any suitable file share method from teamviwer to es explorer.


you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.
