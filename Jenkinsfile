pipeline {
    agent any

    tools {
        nodejs '25.2.1'
    }

    stages {

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Build Angular App') {
            steps {
                bat 'npm run build'
            }
        }


    }
}