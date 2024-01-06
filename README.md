# Cloudintegration Project

# Github Interface
Create a branch from a new issue. ‘feature/1-add-h2-database’

# Terminal Branch feature 1-
git fetch origin

git checkout feature/1-add-h2-database

gradlew build

git commit -m 'Add h2 database'

git push

# Github Interface
Create Pull Request
Create a workflow to compile the project 
Java with gradle
Assure the Java version

# Terminal Branch Main
git update-index --chmod=+x ./gradlew

git commit -m 'Add rights'

git pull

# Github Interface
Create a branch from a new issue. ‘feature/1-add-h2-database’

# Terminal Branch feature/2-
git fetch origin

git checkout feature/2-as-user-i-should-see-a-default-webservice

# IDE Interface
Create 2 directory under src.main.java.fr.efrei.server: web.rest(2 directories web + inside it rest)

inside web.rest create StudentRessource

Put code Hello world inside serverApplication

run gradlew build

check http://localhost:8080/api/students

If it's work congratulation !

Now you can commit and push code

# Terminal Branch feature/2-
git add .
git commit -m "add StudentRessource"
git push
