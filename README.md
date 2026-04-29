git clone https://github.com/yourname/template.git new-project-name

cd new-project-name

rmdir /s /q .git

git init

git add .

git commit -m "Initial commit from template"

git remote add origin https://github.com/yourname/new-project-name.git

git push -u origin main

Rename pom.xml

<artifactId>new-project-name</artifactId>
<name>new-project-name</name>

application.properties


mvn -f databaseConnection clean package -DskipTests
dir databaseConnection\target\classes\com\database


mvn -f databaseConnection -DskipTests package

java -jar databaseConnection\target\database-0.0.1-SNAPSHOT.war


mvn spring-boot:run
