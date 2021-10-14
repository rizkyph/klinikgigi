# klinikgigi
Steps to Setup

Clone the repository
git clone https://github.com/rizkyph/klinikgigi.git

Configure PostgreSQL
First, create a database named klinikgigi. Then, open src/main/resources/application.properties file and change the spring datasource username and password as per your PostgreSQL installation.

Run the app
Type the following command from the root directory of the project to run it -

mvn clean spring-boot:run

Alternatively, you can package the application in the form of a JAR file and then run it like so -

mvn clean package java -jar target/klinikgigi-0.0.1-SNAPSHOT.jar The application will start on the default port 8080.
