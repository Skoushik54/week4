pipeline {
    agent any
    stages {
        stage('Execute Java Program') {
            steps {
                script {
                    def javaFile = 'file1.java'
                    bat "javac ${javaFile} && java file1"
                }
            }
        }
        stage('Execute Python Program') {
            steps {
                script {
                    def pythonFile = 'file2.py'
                    bat "C:\\Users\\samba\\AppData\\Local\\Microsoft\\WindowsApps\\python ${pythonFile}"
                }
            }
        }
    }
}
