pipeline {
    agent any
    stages {
        stage('Test Branch') {
            steps {
                script {
                    if (env.BRANCH_NAME == 'testing') {
                        sh 'echo this is a test branch'
                    }
                }
            }
        }
    }
}
