pipeline {
agent { dockerfile true}
    stages {
        stage('Cloning Git') {
            steps{
                sh 'echo checking out source code'
            }
        }
        stage('SAST') {
            steps {
                sh 'echo SAST stage'
                }
        }
        stage('Build-and-Tag') {
            steps{
                sh 'echo Build and Tag'
            }
        }

    }
}