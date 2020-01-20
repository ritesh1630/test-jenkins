pipeline{
   agent none 
   stages{
     stage('build')
        {
           when {
              changelog '.*some_text.*'
           }
           steps{
              echo "hello world changelog"
           }
        }
   }
   
}
