pipeline {
    agent any

    stages {
        stage('GitHub Checkout Test') {
            steps {
                // Checkout the code from GitHub to test the connection
                echo "Checking out code from GitHub..."
                git url: 'https://github.com/Siddhanth03/jenkins.git', credentialsId: 'ba247434-cc58-4522-ad60-9d7caf952fa7'
            }
        }

        stage('Test') {
            steps {
                // A simple message to confirm the pipeline is running
                echo "Jenkins is successfully connected to GitHub!"
            }
        }
    }
}
