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
       post{
        success{
                    build job: 'testpipeline1', parameters:[string(name:'STR_VAL',value:'the name')]
    } 
    }
}
