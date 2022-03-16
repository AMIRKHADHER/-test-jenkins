pipeline {
    agent any

    tools {
        maven '3.8.4'
    }

    stages {
        stage('Get maven version') {
            steps {
                sh 'mvn --version' 
               
            }
        }
    }
}