pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('echo info') {
            steps {
                sh "echo 'Hello World!'"
            }
        }
    }
}
