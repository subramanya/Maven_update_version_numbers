# Maven_update_version_numbers
In this example, the local POM will be set to the version that is provied in the command line below:

mvn --batch-mode release:update-versions -DdevelopmentVersion=1.2.0-SNAPSHOT

We can use the commond to update the version number of all pom.xml files in the project using single command.

Note: if you want to change version of a perticular module then go to the module folder and then run the command. 
Then you need to manually update the version number for this module in all other the pom.xml files where this module as a dependency or parent.



Notes:
Specify versions on the command line.
You may want to specify the version(s) to use on the command line. This can be useful for example if you are running the update in non-interactive mode. The update-versions goal can use the same properties used by the prepare goal for specifying the versions to be used.
