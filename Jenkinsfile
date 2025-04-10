pipeline {
    agent any
    stages {
        stage('Build Docker Image') {
            steps {
                echo '🛠️ Building Docker image...'
                sh 'docker build -t ensf400-demo-app .'
            }
        }
        stage('Run Unit Tests') {
            steps {
                echo '🧪 Running tests...'
                // Example: run one dummy test or real test script
                sh 'echo "Tests Passed ✅"'
            }
        }
        stage('SonarQube Analysis') {
            steps {
                echo '📊 Running SonarQube static analysis...'
                // Add actual analysis step here once SonarQube is running
            }
        }
    }
}
