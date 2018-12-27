pipeline {
    agent any  
    stages {
        stage('Code Quality Check') { 
            steps { 
               sh "mvn clean package"
            }
        }
         stage('Code coverage') { 
            steps { 
               echo 'This is a code coverage stage.' 
            }
        }
         stage('Compile') { 
            steps { 
               echo 'This is a compile stage.' 
            }
        }
         stage('Deploy') { 
            steps { 
               echo 'This is a deploy stage.' 
            }
        }
    }
}
