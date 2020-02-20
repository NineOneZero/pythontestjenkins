pipeline {
    agent any
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                  chmod u+x ./helloworld.py
                  python helloworld.py
                  '''
            }
        }
    }
}