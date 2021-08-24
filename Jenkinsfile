pipeline {
     agent any
     stages {
        stage("Build") {
            steps {
                bat 'npm install'
                bat 'npm run build'
            }
        }
        stage("Deploy") {
            steps {
              echo 'Build ready for deployment'
              bat 'rmdir C:\\jenkins-react-app /s'
              echo 'rmdir completed'
              bat 'copy ${WORKSPACE}\build/ C:\\jenkins-react-app'
              echo 'copy completed'
                 
            }
        }
    }
}







