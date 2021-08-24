pipeline {
     agent any
     stages {
        stage("Deploy") {
            steps {
              echo 'Build ready for deployment'
           
              bat 'xcopy ${WORKSPACE}\build C:\\jenkins-react-app'
              echo 'copy completed'
                 
            }
        }
    }
}







