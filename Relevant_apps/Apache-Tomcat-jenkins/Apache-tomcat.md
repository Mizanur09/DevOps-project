# Run Jenkins with Apache Tomcat
######Precondition

	$$$$ Java must be install on the mechine
	$$$$ jenkins.war file should have

# Download Apache Tomcat

	$ Navigate to (http://tomcat.apache.org/)
	$ Click on Tomcat version (latest -1) from download on the left side bar
	$ Make sure to download tomcat vertion (latest -1)

# On the windows
	
	$ Navigate to Download folder and find Tomcat 
	$ Unzip Apache Tomcat
	$ Navigate to Jenking folder and copy Jenkis.war to Tomcat webapp folder


#  Make all the files exeutable
	
	$ Navigate to tomcat bin folder
	$ type (chmod +x *.sh)
		Explanetion 
		=> chmod = getting permition
		=> + = adding secound command
		=> x = making all file exeutable
		=> *.sh = any file with .sh should be made exeutable.
	$ Start tomcat by running following line on command prompt(./startup.sh) from bin directory
	$ Confermation text on command Prompt (Tomcat stated)
	$ Apache Tomcat should start with (localhost:8080)

# Navigate to localhost:8080 using WebBrowser
	
	$ Tomcat page should display
	$ NAvigate to Jenkins (localhost:8080/jenkis)

# Stop the Tomcate
	
	$ Navigate to Tomcat bin folder on window
	$ run (./shutdown.sh)
	$ Navigate to localhost:8080/jenkins on BewBroser
		Should throw error (404 page not found)