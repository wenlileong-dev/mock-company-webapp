pipeline {
    agent any
    stages { 
        stage('Build') {
            steps {
                echo './gradlew assemble'
            }
        }
        stage("Test"){
          steps{
            echo './gradlew test'
          }
        }
    }
}