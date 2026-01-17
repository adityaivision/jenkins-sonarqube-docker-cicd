pipeline {
    agent any

    stages {
        stage 'Checkout' {
            steps {
                echo 'Checking out source code...'
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm install'
                echo 'NPM Version': sh 'npm -v' // Example build command
            }
        }
}
}
