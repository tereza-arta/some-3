pipeline {
    agent any
    stages {
        stage('stage 1') {
            steps {
                echo "Hello from me...."
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
               sh 'chmod +x file.sh'
               sh 'ls -lah'
            }
            
        }
    }
}
