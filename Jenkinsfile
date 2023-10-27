pipeline {
    agent { docker { image 'maven:3.9.5-eclipse-temurin-17-alpine' } }
    stages {
        stage('build') {
            steps {
                echo 'About to run mvn --version'
                sh 'mvn --version'
                echo 'Ran mvn --version'
            }
        }
    }
}