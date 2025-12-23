pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out from GitHub'
            }
        }

        stage('Build with Maven') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}
