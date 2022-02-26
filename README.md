# Server Tracker List
This repository contains a list for servers to be displayed on the server tracker.

The server tracker is viewable at:

https://tracker.goldenedit.dev

https://tracker.vanillapvp.net

# Adding your own server
To add your own server please make a Pull request.

Here is a short guide on how to format your server to add:

  }, <- Make sure to edit the line above your server that you would like added to unclude a comma (JSON formatting)
	{
		"name": "ServerName", <- Your servers name
		"ip": "serveripaddress.net", <- Your servers IP Address
		"type": "PC" <- Don't touch this
	}
