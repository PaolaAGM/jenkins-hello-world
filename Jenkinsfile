pipeline {

       agent any

       environment {
            PYTHON_HOME = 'C:/Users/paora/AppData/Local/Programs/Python/Python311'
       }

       stages {

         stage('Build') {

            steps {

               script {

               // Choisissez la commande en fonction de votre script

               sh 'python hello.py' // Pour Python

               // sh 'javac HelloWorld.java && java HelloWorld' // Pour Java

               }

            }

        }

    }

}
