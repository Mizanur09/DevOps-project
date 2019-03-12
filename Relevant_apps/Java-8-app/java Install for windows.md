# Steps by Steps java installation process
		
		* Go to Control panel on windows
		* Open System and Security
		* Open System
		* Look for System Type (64-bit Operating System, x64-based Processor) and close the folder.

# {Step 1} Open the Browser 

	*	Navigate to (https://java.com/en/download/)
	*	Click on "Agree and start Free Download"

# {Step 2} On the windows/Computer

	* Locate the java.exe file in the folder
	* 	Double click to install java 
	*	PopUp wil display with following option on the bottom
		*  [Next] [Canel]
		*  Click on [Next]

# On the 2nd page 

	* Click on [Next] again

# On the 3rd page 

	* Keep the default location
	* Click on [Next] again

# On the 4th and last page 

	* Click on [Finish]

# {Step 3} On the windows/Computer
	
	* Naviget to "Program Files" (C:/Program files)
	* Find "Java" and open the folder
	* Following folder is present
		* Jdk
		* Jre

# {Step 4} On the start menu 
	
	* Search "ENVIRONMENT VARIABLE" and open it
	* Click on Environment variable on the modal 
		2 part will display
		[User variable for user] and [System Variable]

# {Step 5} On the variable for user
	
	* Click on {New} button
	* Variable name: [JAVA_HOME] all capital with under scro
	* Variable value: [C:\Program Files\java\jdk] copy the path of "jdk"
	* Click [Ok] button

# {Step 6} On the System Variable
	
	* Click on path and add jdk and jre bin folder.
	* Back to folder open JDK then bin folder and copy the path
	* on the environment path add folder locatioin [C:\Program Files\Java\jdk\bin\]
	* Repeat the same steps for JRE [C:\Program Files\Java\jre\bin\]
	* Click [ok]
	* Click [Ok] for the next window as well

# {Step 7} On the commend line
	
	* Open start manu
	* Search "cmd"
		$$ type on cmd  
		* "which java" (should show the path of java)
	* "java -version" (should show the version number of current java)
	* "javac" (should show multiple option for java)

## shoule be able to successfuly install and add path of java on your environment. :)
