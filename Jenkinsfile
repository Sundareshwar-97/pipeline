pipeline {
    agent any

    stages{
        stage('python stage'){
            steps{
                sh "python3 pythonscript.py"

            }
        }
        stage('shell stage'){
            steps{
                sh "./shellscript.sh"

            }
        }
        
    }
}