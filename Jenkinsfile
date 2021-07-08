pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Devito from Mars'
                        echo 'We are starting the testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                        echo 'Hai in Mercedes'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                        echo "hai in avion"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}