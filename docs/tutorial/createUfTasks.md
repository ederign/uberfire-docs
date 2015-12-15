#Creating UF Tasks Project

Your UF Tasks project will follow the standard Maven project layout. So let's create it using our archetype.

## Creating UF Tasks Project

 In a command line, run the archetype to create your first app.

```
$ mvn archetype:generate -DarchetypeGroupId=org.uberfire -DarchetypeArtifactId=uberfire-project-archetype -DarchetypeVersion=0.7.4.Final
```

 Maven will ask for your groupId, let's use:
```
org.uberfire
```
For the artifactId value:
```
uftasks
```
For version
```
1.0-SNAPSHOT
```
For package
```
org.uberfire
```
Use default value for package, for capitalizedRootArtifactId use:
```
UFTasks
```
Confirm your changes and then you should see the message:
```
[INFO] ---------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ---------------------------------------------------------
[INFO] Total time: 3:32.347s
[INFO] Finished at: Wed Jan 14 20:30:27 BRST 2015
[INFO] Final Memory: 29M/959M
[INFO] ---------------------------------------------------------
````
## Building your App

To build your app, go to directory uftasks, build the project in maven and wait for the build finish.

```

$ cd uftasks
$ mvn clean install

```
You should see the maven build success message again.

## See it work!

How about running our project?
```
$ cd uftasks-showcase/uftasks-webapp
$ mvn clean gwt:run
```
Wait for GWT console build your app:

![gwt build](gwt-console.png)

Click on "Launch Default Browser" to open your Uberfire App. Log in as admin (Username) with admin (as Password). You should see our Hello World.

![app start](appStart.png)

When you see that, you are good to go.
