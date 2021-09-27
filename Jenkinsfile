pipeline {
    agent any
    stages {
        stage ('Initialize') {
            steps {
                echo  "Initializing the Code File"
            }
        }
 
        stage ('Build') {
            steps {
                echo 'Hello profinch'
            }
        }
 
         stage ('Deploy') {
            steps {
                echo 'Deployed an Artifact'
            }
             
        }
         docker tag hello-profinch 10.20.3.10:5000/mourya-profinch


          docker push 10.20.3.10:5000/hello-profinch


    }
}
