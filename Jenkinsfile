pipeline {
   agent any

   stages {
      stage('Build'){
         steps {
            echo "Building the java-project ..."
            ant -f build.xml -v
         }
      }
   }

}
