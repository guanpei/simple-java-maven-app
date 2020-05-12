pipeline {
    echo "---${env.BUILD_NUMBER}---"
    echo "---${currentBuild.result}---"
    agent { docker 'maven:3.3.3' }
    echo "-----1111111-----"
    stages {
            stage('Build') {
                steps {
                    bat 'mvn --version'
                }
            }
        }
}