## Installation

To install and run the application an active internet connection is required. Before this project can be build, the
following dependencies must be installed and configured on the candidates machine:

### 1: JDK 17

Download and install any version of the [JDK 17](https://www.oracle.com/java/technologies/downloads/#jdk17-windows).
Install JDK in a folder whose path does not contain spaces. Also make sure to set the environmental variable JAVA_HOME
in your system. The variable must point to your JDK folder (
absolute path). The path of the "\jre\bin" folder under the JDK folder should also be **prepended** to the PATH system
variable.

### 2: Maven Version 3.x

Download and install any version of [Maven 3](https://maven.apache.org/download.cgi). Install Maven in a folder whose
path does not contain spaces. Make sure to set the environmental variables M2_HOME and M2 in your system. The M2_HOME
variable must point to the maven folder (absolute path). The M2 variable must point to the "bin" folder under the maven
folder (absolute path). The absolute path of the "bin" folder under the maven folder (M2) should also be **prepended**
to the PATH system variable.

### 3: Node.js (Optional)

Node.js is used to run a development web server and build the project. Depending on your system, you can install Node.js
either from source or as a pre-packaged bundle.

### 4: Compile and start App

Navigate to the project folder and execute the command `mvn clean install`

This should compile your application. When this process finishes navigate to `/server` folder and
run `mvn spring-boot:run`

Navigate to http://localhost:8080 in your browser to open the application. To terminate the application, just terminate the execution of the previous command `Ctrl + C`.

After making changes to the code you may stop the application and repeat step `4`

More information regarding the components of the Application can be found in further README files in each of the project
modules.