pipeline {
    agent any  
    stages {
        stage('Code Quality Check') { 
            steps { 
         #      git 'https://github.com/jglick/simple-maven-project-with-tests.git'
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
