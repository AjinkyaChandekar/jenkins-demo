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
                cp '/Users/mac/Jenkins_Home/workspace/pipeline2/README.txt /Users/mac/'
            }
        }
    }
}
