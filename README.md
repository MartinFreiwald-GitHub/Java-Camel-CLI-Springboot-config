# Java-Camel-CLI-Springboot-config
Visual Studio setting up Java, Apache Camel, Apache Springboot.  The source code for this is forked from Github here.  https://github.com/apache/camel


# Addtion to this project I will add Spring boot and Spring boot DATA MongoDB.  I will get the source code from https://github.com/spring-guides/gs-accessing-data-mongodb.
I will be using Windows as my operating system for all of this.

Download MongoDB commumity 8.0 msi download and then download from same site MongoDB Community 8.0 zip download. Just change the selection from msi to zip.  Uses this video from Youtube as a guide.  https://www.youtube.com/watch?v=gB6WLkSrtJk

# Once that is complete and you can log into to MongoDB 8.0 shell in the command line interperter for the Windows installation.  Follow these instructions below from https://spring.io/guides/gs/accessing-data-mongodb#initial

Starting with Spring Initializr
You can use this pre-initialized project and click Generate to download a ZIP file. This project is configured to fit the examples in this tutorial.

To manually initialize the project:

Navigate to https://start.spring.io. This service pulls in all the dependencies you need for an application and does most of the setup for you.

Choose either Gradle or Maven and the language you want to use. This guide assumes that you chose Java.

Click Dependencies and select Spring Data MongoDB.

Click Generate.

Make a snapshot or Print-screen copy of the Spring Initializer.  So you can correct the changes you made in the Group, Artifact and Description field.  You will need this to correct the Customer.java file that is located in the file path: gs-accessing-data-mongodb-main/complete/src/main/java/com/example/accessingdatamongodb/Customer.java

Download the resulting ZIP file, which is an archive of a web application that is configured with your choices.

Extract the file to Your custom named folder.  That is the folder you made through the Java Project Folder using the Visual Studio Editor IDE button Called create a "Create Java Project" Button.
https://www.youtube.com/watch?v=ArW93visVhc  see 3.00 time on the video and prior and past.  Referrnence will be this website.  https://code.visualstudio.com/docs/java/java-tutorial  Now you can cross reffernce the Group and Artifact as well as correct directory path.

If your IDE has the Spring Initializr integration, you can complete this process from your IDE.
You can also fork the project from Github and open it in your IDE or other editor.





