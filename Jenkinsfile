pipeline {
    // Directives
    agent any
    tools {
        maven 'maven'
    }

    stages {
        // Specify various stage within stages

        // Stage1 Build
        stage('Build') {
            steps {
                sh 'mvn clean install package'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
