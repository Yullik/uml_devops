pipeline {
    agent any
    stages {
        stage('Main Branch') {
            steps {
                script {
                    if (env.BRANCH_NAME == 'main') {
                        sh 'echo this is the main branch'
                    }
                }
            }
        }
    }
}
