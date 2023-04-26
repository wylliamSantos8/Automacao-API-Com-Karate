pipeline {
    agent any

    tools{
        jdk "JDK11"
        maven "MAVEN"
    }
    stages {
        stage('Java version') {
            steps {
                echo "PATH = ${JAVA_HOME}"
                bat 'java -version'
            }
        }
        stage('Maven Version') {
            steps {
                echo "PATH = ${MAVEN}"
                bat 'mvn -version'
            }
        }
    }
}