pipeline {
   agent any

   stages {
      stage('Checkout') {
         steps {
            git 'https://github.com/Yuvaranjani123/hello-world-java.git'
         }
      }
      stage('Build'){
        steps {
            sh 'javac HelloWorld.java'
        }
      }
   }
}
