pipeline {
    agent any
    stages {
        stage('stage 1') {
            steps {
               script {           
                def S_VAR = "hello"
                env.S_VAR = S_VAR
                        }
                    } 
                }
        stage('stage 2') {
            steps {
               script {
                echo "This is your S_VAR, $S_VAR"    
                } 
            }
        }
    }
}
