# EmailVerifier
This python script can be used to verify emails

1. This will first filter all emails with invalid emails format using regex
2. Using dnslookup and smtp simple handshake verify all valid format emails

I have verified this script it google colab and it is working without any issue

Note: if you run it locally it may not work because of your router/isp firewall, you can fix that using port forwarding and guess what in some routers
 (like mine) this setting is a bit complex so I didn't do that and if you don't want to lose your sanity, kindly use collab or ec2 or any virtual servers
