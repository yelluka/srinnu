@Library('MySharedLibrary') _

pipeline {
    agent any

    stages {
        stage('Greet') {
            steps {
                mySharedFunction('John')
            }
        }
    }
}
