pipeline {
   agent any
   options {
       disableConcurrentBuilds()
   }
   stages {
      stage('Hello') {
         steps {
            sleep (time :10 , unit: 'SECONDS')
            echo 'Hello World'
         }
      }
   }
}
