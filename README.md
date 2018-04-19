# Liferay-SimpleExample


To run this project you will need a portal of Liferay.

Here the link of Liferay to download the portal.

https://www.liferay.com/es/downloads

To develop with Liferay you need the Liferay IDE.

https://web.liferay.com/es/downloads/liferay-projects/liferay-ide

After downloaded the portal bundle unzip it and create a portal-ext.properties file.
File it with the code of the following url:

https://dev.liferay.com/es/discover/reference/-/knowledge_base/7-0/database-templates

Create a database and point to it in your portal-ext.properties.

Get the jar of mysql connector in the maven repository webpage.

https://mvnrepository.com/artifact/mysql/mysql-connector-java/6.0.6

And paste it in your tomcat/lib/ext.

Create a Liferay workspace project in your eclipse IDE.
Open the gradle.properties file and point in the liferay.workspace.home.dir line to your LiferayHome directory.

When you finish with all of this you are able to run the the first time your application.

Go to your tomcat/bin directory and use ./startup to run your projcet and ./shutdown to stop it.



