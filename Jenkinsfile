#!groovy

pipeline {

    agent any
    
    stages {
        stage('Git clone') {
            steps {
                echo "-=- preparing project environment -=-"
                // Python dependencies
                sh '''git clone https://github.com/charan271271/cloudmoniteringapp.git'''
            }
        }
    }
}