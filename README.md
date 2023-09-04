# Squid-Proxy

└─$ sudo apt install squid -y

└─$ sudo nano /etc/squid/squid.conf


http_port 3128  change it to other port example 8080

Find this letter "And finally deny all other access to this proxy"
change deny to allow on bottom line 

http_access allow all

save it with Ctrl+x and  Press enter then press y and hit enter on your keypad

└─$ sudo systemctl restart squid

Enjoy :)
