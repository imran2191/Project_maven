pipeline {
    agent any
    stages {
        stage('---SCM checkout---') {
            steps {
                sh "git clone 'https://github.com/imran2191/Project_maven.git'"
            }
        }
        stage('--maven Build--') {
            steps {
                sh "mvn package"
            }
        }
    }
}
