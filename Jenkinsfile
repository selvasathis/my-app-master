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
    }
}