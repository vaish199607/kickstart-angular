pipeline {
    agent any
stages {
     stage('install dependencies and build') {
            steps {
               sh "npm install"
               sh "npm run build"
            }
        }
     stage('Deploy') {
         steps {
            sh "cp /var/lib/jenkins/workspace/angular/dist/kickstart-angular/*  /var/www/html"
          }
        }
    }
}

