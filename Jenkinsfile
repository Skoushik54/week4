pipeline {
    agent any
    stages {
                stage('Execute Java Program') {
            steps {
                script {
                    def javaFile = 'YourJavaProgram.java'
                    bat "javac ${javaFile} && java YourJavaProgram"
                }
            }
        }
        stage('Execute Python Program') {
            steps {
                script {
                    def pythonFile = 'YourPythonScript.py'
                    bat "python ${pythonFile}"
                }
            }
        }
    }
}