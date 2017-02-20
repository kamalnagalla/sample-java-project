
Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {s
            steps {
                sh 'mvn --version'
            }
        }
    }
}

