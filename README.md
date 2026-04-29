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
