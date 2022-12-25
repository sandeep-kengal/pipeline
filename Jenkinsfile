pipeline {
 agent any
     stages { 
       stage ('First') { 
        steps {
         
                 sh '''  "$BUILD_NUM" '''
      }
       }  
     
        stage ('Second') {
         steps {
          echo ''' echo "hi" '''
          }
        } 
   }
   }
