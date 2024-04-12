pipeline {
    agent any
    
    stages {
        stage('Parallel Stage') {
            parallel {
                stage('Stage 1') {
                    steps {
                        echo 'Running Stage 1'
                        // Your commands for Stage 1
                    }
                }
                stage('Stage 2') {
                    steps {
                        echo 'Running Stage 2'
                        // Your commands for Stage 2
                    }
                }
                stage('Stage 3') {
                    steps {
                        echo 'Running Stage 3'
                        // Your commands for Stage 3
                    }
                }
            }
        }
    }
}
