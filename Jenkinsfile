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
                    def pythonDir = 'C:\\Users\\samba\\OneDrive\\Desktop\\devops lab\\week4'  // Corrected with escaped backslashes
                    bat "cd ${pythonDir} && python ${pythonFile}"
                }
            }
        }
    }
}
