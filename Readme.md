# mvn clean install
	it install the plugin into local repository
	
	Execute The Plugin
	There are two ways to execute the plugin.

	The longer way: To execute the plugin, we have to use the format: 

	mvn groupId:artifactId:version:goal

	So, in this case, it will be

	mvn com.sample:myfirst-maven-plugin:1.0-SNAPSHOT:hello

	The shortcut: Here is an interesting article regarding naming conventions. As we are following the aforementioned proper plugin naming conventions (${prefix}-maven-plugin), 
	we can execute our plugin like so: 
	mvn myfirst:hello