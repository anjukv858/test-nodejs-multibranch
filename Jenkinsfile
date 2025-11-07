pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application on dev..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application on dev..."'
         }

     }
  
   	}

   }

