pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch code"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is Sprint1 branch code"'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is development branch........."'
            }
        }  
    }
}
