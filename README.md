﻿# maventest
git init
git add .
git commit -m "Initial Maven project for Azure Pipelines"
git branch -M main
git remote add origin https://github.com/<your-username>/maventestazure.git
git push -u origin main


mkdir maventest1
cd maventest1
mvn archetype:generate \
  -DgroupId=com.dineshonjava \
  -DartifactId=Javateam \
  -DarchetypeArtifactId=maven-archetype-quickstart \
  -DinteractiveMode=false
