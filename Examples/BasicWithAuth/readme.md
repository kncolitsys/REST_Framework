To run this example:

First, the Relaxation working copy needs to be accessible from "/Relaxation" in your testing environment. I suggest adding a virtual directory in your web server and a mapping in your CF Administrator.

The first condition having been met, you should be able to hit the following URLs:
	
	To See JSON results for GET requests directly:
	http://localhost/Relaxation/Examples/Basic/index.cfm/product
	http://localhost/Relaxation/Examples/Basic/index.cfm/product/1
	
	You should be prompted by your browser for a username and password. Those are "Maxin" and "Relaxin".
	
I recommend installing a browser plugin like JSONView so that the JSON response is pretty and readable.