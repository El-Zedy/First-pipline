pipeline {
    agent { label 'iti-ubuntu-slave'}

    stages {
        stage('bulid') {
            steps {
                echo 'bulid'
                sh "ls"
            }
        }
        stage('test') {
            steps {
                echo 'test'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy and Goodby'
            }
        }
    }
}

