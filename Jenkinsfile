pipeline {
    agent any

    stages {
        stage 'Checkout' {
            steps {
                echo 'Checking out source code...'
                //checkout branch: 'main', scm: $class: 'GitSCM', userRemoteConfigs: [[url: 'https://github.com/adityaivision/jenkins-sonarqube-docker-cicd.git']]
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


// This Jenkinsfile defines a simple CI pipeline with two stages: Checkout and Build. The Checkout stage checks out the source code from the SCM repository, and the Build stage installs npm dependenci
// git was missing from jenkins server
// new
//
