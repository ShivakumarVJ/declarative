pipeline {
    agent any
    stages {
      stage ('first stage') {
         steps {
           sh " echo 'This is my declarative pipeline' "
         }
      }
        
      stage ('build') {
         steps {
           echo 'This is build stage'
         }
      }
        
      stage ('Test') {
         steps {
           echo 'this is test stage'
         }
      }
      stage ('Deploy') {
         steps {
           sh 'make publish'
         }
      }        
    }
}
          
            
    
