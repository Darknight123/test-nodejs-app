pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           bat 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           bat 'echo "testing application..."'
        }
      }

         stage("Deploy nodejs application") { 
         steps { 
           bat 'echo "deploying application..."'
         }

     }
  
   	}

   }
