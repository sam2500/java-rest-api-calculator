pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/sam2500/java-rest-api-calculator.git'
                sh './mvnw clean compile'
            }
        }
    }
}
