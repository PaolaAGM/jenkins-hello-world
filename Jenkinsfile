pipeline {

       agent any

       environment {
            PYTHON_HOME = 'C:/Users/paora/AppData/Local/Programs/Python/Python311'
            PATH = '${env.PATH};${PYTHON_HOME}'
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
