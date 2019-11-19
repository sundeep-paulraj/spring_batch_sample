pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('Check current batch job versions') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('Deploying all the batch jobs') {
            steps {
                sh 'Deploy all the batch jobs and display the output'
            }
        }
    }
}