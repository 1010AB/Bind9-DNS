# Bind9-DNS
This will consist of the config file for different Bind9 configuration and how to build a full Bind9 DNS server 
the Bind9 Dns setup in this repo will consist of the following dns server type all working together for a lab 
Domain Practicelab.com 
Type of Dns server include 
Master server 
Slave server 
forwarder 
DnsSec server 
DNS view server 
also note that the Master server in this scene will be my SOA all of these server are runing individually on Docker 
i will be have three client container running as well, which will be testing the following
DNSsec 
Slave server
and the View DNS that seperate based on who is asking. 
