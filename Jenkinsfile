pipeline {
    agent any
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                  python helloworld.py
                  '''
            }
        }
    }
}