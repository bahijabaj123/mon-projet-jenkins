pipeline {
    agent any
    
    stages {
        stage('Checkout Git') {
            steps {
                echo '🎯 PHASE 1: RÉCUPÉRATION DU CODE'
            }
        }
        
        stage('Build Maven') {
            steps {
                echo '🔨 PHASE 2: COMPILATION'
            }
        }
        
        stage('Tests Unitaires') {
            steps {
                echo '🧪 PHASE 3: TESTS'
            }
        }
    }
    
    post {
        always {
            echo '📊 PIPELINE TERMINÉ - 3 PHASES CI IMPLÉMENTÉES'
        }
    }
}
