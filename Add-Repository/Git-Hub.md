# follwing steps need to be done before stablising the jenking connections happens
	
	#*****Precondition*****# 
	$$ Create a gitHub accoutn 
	$$ Create a project in getHub account
	$$ Clone the Project in to the mechine
	$$ Add a File to gitHub Project (README.md)
	$$ Add some text in the file
	$$ need to keep Jenkins up and running.. (Read the jenkins README for more info)

# Cteating getHub account
	
	$ Navigate to GitHub (https://www.gitHub.com)
	$ Signup 
	$ Create project
	$ Clone the Project URL

# On the windows
	
	$ Open commend prompt
	$ Navigate to desier folder 
	$ Type on cmd (git clone URL) enter

# In GitHub from Browser
	
	$ Sign in, then select the related repository.
	$ Click on "Settings" on the right panel.
	$ Then click on "Webhooks & Services" on the left panel.
	$ Click on the "Add WebHook" Button.
	$ Paste the copied URL in the URL form field.
		*Example* jenkins URL (localhost:8080)
	$ Select "application/json" as the content type.
	$ Select "Let me select individual events" and check "Issues".
	$ Leave the "Active" checkbox checked.
	$ Click on "Add webhook" to save the webhook

# Open Jenkins in the WebBroser
	
	$ Click on [Manage Jenkins] from the left column
	$ On the Manage Jenkins click on [Manage Plugins]
	$ On the Manage plugins search box search [git plugins]
	$ Click on the check box right below the git plugins.
	$ Click on [Download now and install after restart] Should take you to the jenkis home page

# Add Github account and Configuration

	$ Click on [New Item] from the left column.
	$ Provide itam name in to [Enter an item name box]
	$ Select [Freestyle Project] from the list.
	$ Click on the [Ok] button from buttom.
	
	$ Configaretion page should open all box
	$ Add Description (optional)
	$ Select check box right below Descriptio (As needed othewise leave default)

# Source Code Management
	
	$ Select git from the checkbox
	$ Provide Repository URL + .git (master Branch)
	$ Add Credentials (If Private repository)

 #**** Keep Everything else default ****#
