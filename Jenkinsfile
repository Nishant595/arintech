pipeline{
    agent {label "agentfarm" }
    stages {
        stage('Delete the workspace'){
            steps{
                cleanWs()
            }
        }
       stage('Second Stage'){
           steps {
               echo "second stage"
           }
         }     
        stage ('Third stage'){
            steps{
                echo "Third Stage"
            }
        }
      }
  }
