pipeline {
    agent any
    stages{
        stage ('checkout') {
            steps {
                echo 'Checking out from private repo'
            }
        }
        stage ('build') {
            steps {
                echo 'This is the build step!'
            }
        }
        stage ('push') {
            steps {
                echo 'This is the push step!'
            }
        }
        stage ('deploy') {
            steps {
                echo 'This is the deploy step!'
            }
        }
        stage ('test') {
            steps {
                echo 'This is the test step!'
            }
        }
    }
}