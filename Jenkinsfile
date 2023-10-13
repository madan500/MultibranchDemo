pipeline {   
    agent any

    stages {   
        stage('Master branch') { 
            steps { 
               sh 'echo "This is master branch' 
            }
        }
     
        stage('Build') { 
            steps { 
               sh 'echo "Building application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
