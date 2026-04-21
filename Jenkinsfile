pipeline {
    agent any
    tools {
        maven 'Maven Default'
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                sh 'mvn -B -Dskiptests clean package'
            }
        }
    }
}
