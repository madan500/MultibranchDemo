pipeline {   
    agent any

    stages {   
        stage('QA branch') { 
            steps { 
               bat 'echo "This is qa branch' 
            }
        }
     
        stage('Build') { 
            steps { 
               bat 'echo "Building application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                bat 'echo "Deploying application..."'
            }
        }  
    }
}
