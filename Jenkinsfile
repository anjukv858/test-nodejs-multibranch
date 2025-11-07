pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test- QA') { 
        steps { 
           sh 'echo "testing application n QA env..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application on QA env..."'
         }

     }
  
   	}

   }

