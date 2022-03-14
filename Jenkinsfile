node {
   stage('Preparation') {
      git 'https://github.com/rosscg/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}