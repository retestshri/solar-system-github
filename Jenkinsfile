pipeline{
    agent any

    stages{
        stage("checkout scm")
        {
            steps{
                sh """
                    node -v
                    npm -v
                """    
            }
        }
    }
}