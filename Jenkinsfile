
pipeline {
  
    agent none
    
    stages    {
      
        stage('input') {
          agent any 
          when {
           beforeInput true
           branch 'qa'
        }
      }
        stage("build") {
          
            steps {
                echo 'buid steps 1 test aplications $branch (qa)'
                       }
                  }
        stage("test") {
            
            steps {
                echo 'test steps $branch (qa)'
                      }
                  }
        stage("deploy1") {
          
            steps {
                echo 'deploy steps $branch (qa)'
                          }
                  }
              }
        } 
