Disclaimer :
	The following steps needs to be done only if the Android application demo between 2 devices - fails.
	I will try to host this server at my place. However, if it fails at my place due to some reason you can run the server on your laptop to see the demo.


**Pre-requisite:**
	Laptop with Java installed.(Preferably Windows - which was the developer test environment)

**Steps to run the server**
	- Copy xmppserver folder to system. eg: "D:\xmppserver"
	- Open cmd prompt (Goto Start->Run->cmd)
	- Goto the directory where the "xmppserver" folder is copied. eg:"cd /d D:\xmppserver"
	- Run the below commands :
		"javac -cp *;.; XMPPServerApp.java"
		"java -cp *;.; XMPPServerApp"	


Now the Server will start running and open the UI console.



