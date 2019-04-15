  node{
   stage('Checkout'){
     git 'https://github.com/Aakarsh-Bhatnagar/JenkinsTask.git'
   }
    stage('Build')

     {
      sh 'mvn clean install'
       sh 'mvn package'

     }

     stage('Test')

     {

         echo "Test the code"

     }

}


