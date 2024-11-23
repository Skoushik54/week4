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
                    bat '"C:\\Program Files\\Python312\\python.exe" "C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\week4\\file2.py"'
                }
            }
        }
    }
}