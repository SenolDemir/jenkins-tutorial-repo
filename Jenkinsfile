pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Pipeline job with Jenkinsfile"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
