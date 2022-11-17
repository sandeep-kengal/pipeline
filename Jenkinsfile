pipeline 
{
agent any
stages {
stage ( 'job1' ) {
steps {
 echo "This is Build stage"
 sh ''' sleep 5 '''
 }
 }
 stage ( 'test' ) {
  steps {
   echo "hi"
   sh ''' sleep 5 '''
  }
 }
 stage ( 'test1') {
  agent ( "c-projetc')
         
  steps {
   sh '' free -h ''
  }
         }
}
}
