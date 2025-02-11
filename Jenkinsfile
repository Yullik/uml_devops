pipeline {
    agent none  // No default agent, we'll define it per stage
    stages {
        stage('Pipeline 1') {
            agent { dockerContainer { image 'alpine' } }
            steps {
                sh 'echo Running Pipeline 1'
            }
        }
        stage('Pipeline 2') {
            agent { dockerContainer { image 'alpine' } }
            steps {
                sh 'echo Running Pipeline 2'
            }
        }
        stage('Pipeline 3') {
            agent { dockerContainer { image 'alpine' } }
            steps {
                sh 'echo Running Pipeline 3'
            }
        }
        stage('Pipeline 4') {
            agent { dockerContainer { image 'alpine' } }
            steps {
                sh 'echo Running Pipeline 4'
            }
        }
    }
}

