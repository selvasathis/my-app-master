pipeline {
    agent any
    stages {
        stage ('scm checkout') {
            steps {
                script {
                    git branch: 'main', url: 'https://github.com/selvasathis/my-app-master.git'  
                }
            }
        }
        stage ('maven clean') {
            steps {
                script {
                    sh 'mvn clean package'
                }
            }
        }
    }
}