pipeline {
       agent any
   stages {
       stage ('checkout') {
           steps {
               echo 'cloning in to localrepo'
          }
        }
       stage ('build') {
           steps {
               echo 'build the code'
          }
       }
       stage ('test') {
           steps {
               echo 'testing the code'
          } 
       }
      stage ('deploy') {
          steps {
              echo 'deploying the code'
          }
       }
     }
   }

