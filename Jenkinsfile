  node{
   stage('Checkout'){
     git 'https://github.com/Aakarsh-Bhatnagar/JenkinsTask.git'
   }
    stage('Build')

     {
        def mvnHome=tool name: '', type: 'maven'
       sh '${mvnHome}/bin/mvn package'

     }

     stage('Test')

     {

         echo "Test the code"

     }

}


