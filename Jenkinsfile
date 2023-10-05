pipeline {
    tools {
        mvn 'mvn-3.8.5'
    }
    stages {
        stage('clean stage') {
            mvn -B clean
        }
        stage('install stage') {
            mvn -B install
        }
    }
}