pipeline{
    agent any 
    stages{
        stage('test'){
            steps{
                sh """
                echo "hi"
                ls -ltr
                
                """
            }
        }    }
    
    
}
    }
    post {
        always {
          echo 'hi'
         deleteDir()
        }
    }
}
