pipeline {
    agent any

    tools {
        maven '3.8.4'
    }

    stages {
        stage('Get maven version') {
            steps {
                echo 'le step de test'
                sh 'mvn --version' 
                sh 'mvn test' 
               
            }
        }
    }
}