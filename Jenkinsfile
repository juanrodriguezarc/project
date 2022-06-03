pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'building the application'
            // sh 'cd app'
            // sh 'yarn install'
            // sh 'yarn build'
            }
        }

        stage {
            stage('test') {
                steps {
                    echo 'testing the application'
                }
            }
        }
        
        stage {
            stage('deploy') {
                steps {
                    echo 'deploying the application'
                }
            }
        }
    }
}
