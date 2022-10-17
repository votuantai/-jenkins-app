pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git credentialsId: 'MyGitHub', url: 'https://github.com/votuantai/-jenkins-app.git'
            }
        }
    }
}
