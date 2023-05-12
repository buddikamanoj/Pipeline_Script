pipeline{
    agent any

    triggers{
        pollSCM '*/5 * * * *'
    }

    stages{
        stage('Build'){
            steps{
                echo "budilding the code"
            }
        }

        stage('test'){
            steps{
                echo "testing goes here"
            }
        }    
        stage('deliver'){
            steps{
                echo "deliverting to prod"
            }
        }    

                
    }
}
