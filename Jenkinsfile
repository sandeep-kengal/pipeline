pipeline {
 agent any
     stages { 
       stage ('First') { 
        steps {
         catchError(message: 'continue') {
                 sh '''  "$BUILD_NUM" '''
      }
       }  
       }
        stage ('Second') {
         steps {
          echo ''' echo "hi" '''
          }
        } 
   }
   }
