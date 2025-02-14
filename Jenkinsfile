pipeline {
    agent any
    stages {
        stage('GitHub Checkout') {
            steps {
                echo "Checking out code from GitHub..."
                git url: 'https://github.com/Siddhanth03/jenkins.git', branch: 'main' , credentialsId: 'ba247434-cc58-4522-ad60-9d7caf952fa7'
            }
        }
        stage('Test') {
            steps {
                echo "Pipeline is working!"
                echo "bhargv"
            }
        }
    }
}
