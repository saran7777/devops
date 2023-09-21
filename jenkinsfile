pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code...'
                checkout scm  // This command checks out the code from the configured SCM in the pipeline job configuration.
            }
        }
    }
}
