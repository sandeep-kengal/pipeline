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
 stage ( 'test100' ) {
  steps {
   echo "hi"
  }
 }
}
}
