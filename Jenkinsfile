pipeline {   
    agent any

    stages {   
        stage('sprint1 branch new') { 
            steps { 
               sh 'echo "This is master branch new"' 
i
            }
        }
     
        stage('test') { 
            steps { 
               sh 'echo "test application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
