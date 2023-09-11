pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "Build"
            }
        }
        stage('Test') { 
            steps {
                echo "Test"
            }
        }
        stage('Deploy') { 
            steps {
                sh 'cp /Users/mac/JenkinsHome/workspace/pipeline2/README.txt /Users/mac'
            }
        }
    }
}
