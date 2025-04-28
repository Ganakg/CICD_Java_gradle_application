pipeline{
    agent any 
    stages{
        stage("build"){
            steps{
                script{
                    sh 'chmod +x gradbuild'
                    sh './gradlew sonarqube'
                }
                        
            }
        }
    }
}

                   
