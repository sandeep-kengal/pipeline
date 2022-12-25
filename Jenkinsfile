pipeline {
 agent any
     stages { 
       stage ('First') { 
        steps {
            catchError(message: 'continue') {
                 sh ''' echo "$BUILD_NUMBER" '''
      }
        }
       }  
        stage ('Second') {
         steps {
          echo ''' echo "hi"
          }
        } 
   }
   }
