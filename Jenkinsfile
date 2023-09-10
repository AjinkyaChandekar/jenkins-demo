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
                cp /Users/mac/.jenkins/workspace/pipeline2/README.md /Users/mac/
            }
        }
    }
}
