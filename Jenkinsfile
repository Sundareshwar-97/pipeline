pipeline {
    agent any
    environment{
        NAME="sundar"
    }

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