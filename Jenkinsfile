pipeline { 
  
   agent any

   stages {
   
     stage('Checkout') { 
        steps { 
         bat  'echo "Checkout code"'
        }
     }
     
     stage('Compile') { 
        steps { 
           bat 'echo "compile application..."'
        }
      }

      stage('Test') { 
        steps { 
           bat 'echo "Test application..."'
        }
      }
         stage("Package application") { 
         steps { 
           bat 'echo "package application..."'
         }

     }
  
   	}

   }
