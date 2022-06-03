pipeline {
    agent any 

    stages {
        stage("build"){
            steps {
                echo 'building the application'
                // sh 'cd app'
                // sh 'yarn install'
                // sh 'yarn build'
            }
        }
    }
    stages {
        stage("test"){
            steps {
                echo 'testing the application'
            }
        }
    }
    stages {
        stage("deploy"){
            steps {
                echo 'deploying the application'
            }
        }
    }
}

node {
    // groovy script
}