pipeline {   
    agent any

    stages {   
        stage('Master branch is updated') { 
            steps { 
               sh 'echo "This is master branch is updated"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
