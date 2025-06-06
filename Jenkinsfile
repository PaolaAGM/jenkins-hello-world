pipeline {

       agent any

       environment {
            SYSTEM32 = 'C:\\Windows\\System32'
            PYTHON_HOME = 'C:/Users/paora/AppData/Local/Programs/Python/Python311'
            PATH = "${SYSTEM32};${PYTHON_HOME};${env.PATH}"
       }

       stages {

         stage('Build') {

            steps {

               script {

               // Choisissez la commande en fonction de votre script

               bat 'python hello.py' // Pour Python

               // sh 'javac HelloWorld.java && java HelloWorld' // Pour Java

               }

            }

        }

    }

}
