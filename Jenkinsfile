pipeline{
    agent any

    tools {
        nodejs 'nodejs-22.16.0'
    }
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