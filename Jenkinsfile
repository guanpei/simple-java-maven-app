echo "-----1111111-----"
pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
            stage('Build') {
                steps {
                    bat 'mvn --version'
                }
            }
        }
}