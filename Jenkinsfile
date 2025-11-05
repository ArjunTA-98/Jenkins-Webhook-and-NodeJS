pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                // CHANGED: Replaced 'bat' with 'sh' for macOS/Unix shell execution
                sh """
                    echo "Hello Jenkins!"
                    echo "This pipeline runs on a Mac/Unix agent."
                """
            }
        }
    }
}
