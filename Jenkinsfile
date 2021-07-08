pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is devito from outer space'
                        echo 'We are starting the testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
            stage('Extra stage') {
                  steps {
                        echo "Extra Stage - Test"
                  }
            }
      }
}