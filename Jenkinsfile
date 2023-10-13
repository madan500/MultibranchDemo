pipeline {   
    agent any

    stages {   
        stage('DEV branch') { 
            steps { 
               bat 'echo "This is development branch' 
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
