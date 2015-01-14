#5 minutes Introduction
This session teaches you how to build your first Uberfire App in just 5 minutes.

## Prerequisites
This guide assumes you have the following software set up and working on your computer:
* A Java Development Kit (JDK) version 6 or newer

* Maven 3.x

## Creating your first App

 In a command line, run the archetype to create your first app. (TODO Change archetype version after release)


```
$ mvn archetype:generate
    -DarchetypeGroupId=org.uberfire
    -DarchetypeArtifactId=uberfire-project-archetype
    -DarchetypeVersion=0.5.0-SNAPSHOT
```
 Maven will ask for your groupId, let's use:
```
org.uberfire
```
For the artifactId value:
```
demo
```
Use default value for package, for capitalizedRootArtifactId use:
```
Demo
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
## Building your first App

To build your first app, go to directory demo, build the project in maven and wait for the build finish.

```

$ cd demo
$ mvn clean install

```
You should see the maven build success message again.

## See it work!

How about run our first project?
```
cd demo-showcase/demo-webapp
mvn gwt:run
```
Wait for GWT console build your app:

(TODO)
![gwt build](images/gwt_build.tiff)



