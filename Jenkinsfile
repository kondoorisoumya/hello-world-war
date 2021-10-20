pipeline {
    agent any
    environment {
        PATH = "/usr/share/maven/bin/:$PATH"
    }

    stages {
        stage('fetching') {
            steps {
                //echo 'Hello World'
                git 'https://github.com/kondoorisoumya/hello-world-war.git'
            }
        }
        stage('package') {
            steps {
                //echo 'Hello World'
                sh "mvn clean package"
            }
        }
    }
}
