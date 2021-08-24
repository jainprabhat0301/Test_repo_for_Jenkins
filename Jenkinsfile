pipeline {
     agent any
     stages {
        stage("Deploy") {
            steps {
              echo 'Build ready for deployment'
           
              bat 'copy C:\Windows\system32\config\systemprofile\AppData\Local\Jenkins\.jenkins\workspace\Second_Pipeline_Test C:\jenkins-react-app'
              echo 'copy completed'
                 
            }
        }
    }
}







