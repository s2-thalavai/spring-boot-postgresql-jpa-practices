# spring-boot-postgresql-jpa-practices

Build the Whole Project:

    mvn clean install
	
![alt text](./screen-shots/02-build-module-proj.png)
	
Build a Specific Module:

	mvn clean install -pl module-name -am

	-pl: Build this module
	-am: Also build its dependencies

	Ex:

	  mvn clean install -pl 01-pessimistic-locking -am

![alt text](./screen-shots/02-1-build-module-proj.png)
