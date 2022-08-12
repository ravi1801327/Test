pipeline {
    agent {label 'Linux_1'}
    stages{
        stage('Cloning'){
            steps {
                git branch: 'main', url: 'https://github.com/ravi1801327/Test.git'
            }
        }
        stage('Printing'){
            steps {
                sudo chmod 777 test.sh 
                sh 'test.sh'
            }
        }
    }
}
