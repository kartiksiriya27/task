pipeline {
    agent any
 
    stages {
 
 
        stage('Print') {
            steps {
                echo 'new project'
            }
        }
 
        stage('Clone') {
            steps {
                sh 'git clone -b master https://github.com/kartiksiriya27/task.git'
            }
        }
 
    }
}
