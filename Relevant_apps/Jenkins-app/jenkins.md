# Steps by Steps jenkins installation process
	
	* Open web Browser and navigate to (https://jenkins.io/download/)
	* Open your commend prompt from start menu
	* Navigate to folder where jenkins downloaded.
	
	$ Make localhost:8080
	* type on commend prompt (java -jar jenkins.war) Enter
	 ** open WebBrowser and navigate to (localhost:8080) 
	
	$ Make Custom port for jenkins 
	* Type on commend Prompt (java -jer jenkins.war --httpPort=(portNumber)) Enter
		$$Example
			$ localhost:8080 (default)

	** Open WenBrowser and navigate to {localhost:(Custom Port Number)}
	$$ Example
		$ localhost:9090
		$ localhost:909

	for the first time user
	$$ Costomize jenkins page will display with
	{Install suggested plugins} and {Select Plugins to Install}
	$$ Click on [Selec Plugins to install]
	$$ Select all the Plugins as needed 
	$$ Click on Install

	$$ Crete First Admin User page will display with following options
		* Username []
		* Password []
		* Confirm Password []
		* Full name []
		{Cotinue as admin} and {Save and Finish} button


### jenking Stand alone will start and home page will displayed ###