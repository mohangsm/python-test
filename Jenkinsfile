pipeline {
    agent any
    stages {
        stage('checkout app code') {
            steps {
                echo 'This step is to checkout the app code'
		git branch: 'dev',
    			credentialsId: '9b4b6243-8d3b-4a9c-b493-aef4b3f2d880',
    			url: 'https://github.com/mohangsm/python-test.git'
            }
        }
        stage('build') {
            steps {
                echo 'This is a build step'
            }
        }
        stage('test') {
            steps {
                echo 'This is a test step'
            }
        }
        stage('code check') {
            steps {
                echo 'This is a code check step'
            }
        }
    }
}
