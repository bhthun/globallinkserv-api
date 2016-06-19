# Global Link server API
Global Link server API for any apps or program to connecting with sockets.

You can use Global Link API to sent data from anywhere to internet and sent to specific public IP with Global Link API for free.

# Public IP address
You can find connection public IP by connect to http://www.bhthun.tk/serv/netmetatest.php and find Public IP with ini.

# API manual
1. Make sure your software is connected to internet.
2. Bind your software to connect with socket (tcp)
3. Connect to serv2.bhthun.cf:5270
4. Write from {"i": {"tarip": "[Your target public IP]", "data": "[You data that want to sent to target]" }} as string.
5. Sent string in 4. to serv2.bhthun.cf:5270 by TCP sockets
