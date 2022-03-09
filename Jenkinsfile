pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
            echo 'downloading dependencies' 
        }
     }
     
     stage('Test') { 
        steps { 
            echo 'testing application...'
        }
      }

         stage("Deploy application") { 
         steps { 
             echo 'deploying application...'
         }

     }
  
   	}

   }
