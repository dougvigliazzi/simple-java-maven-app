pipeline {
    agent any
    stages {
        stage ('Build') {
            steps{
                sh 'mvn clean package'
            }
        }
        stage ('Unit test') {
            steps {
                sh 'mvn test'
            }
        }
    }

}