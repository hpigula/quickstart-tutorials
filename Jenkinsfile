pipeline {
    agent any
    tools {
        maven 'Maven Default'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -Dskiptests clean package'
            }
        }
    }
}
