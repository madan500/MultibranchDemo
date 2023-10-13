pipeline {   
    agent any

    stages {   
        stage('Master branch') { 
            steps { 
               bat 'echo "This is master branch' 
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
