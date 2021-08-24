pipeline {
     agent any
     stages {
        stage("Deploy") {
            steps {
              echo 'Build ready for deployment'
              bat 'rmdir C:\\jenkins-react-app /q'
              echo 'rmdir completed'
              bat 'copy ${WORKSPACE}\build/ C:\\jenkins-react-app'
              echo 'copy completed'
                 
            }
        }
    }
}







