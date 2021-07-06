pipeline {
    agent any
    environment {
      PATH="/usr/share/maven/bin/:$PATH"
      }
    stages {
        stage('featching') {
            steps {
                //echo 'Hello World'git
                git 'https://github.com/kondoorisoumya/hello-world-war.git'
                
            }
        }
        stage('package') {
            steps {
                //echo 'Hello World'git
                sh "mvn clean package"
            }
        }
    }
}
