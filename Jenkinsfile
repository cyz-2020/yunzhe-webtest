node {

        stage('setup') {
             checkout scm  
            echo 'Hello World nihao'
        }
        stage('test'){
            echo 'start test'
            sh 'python webTest-master/start_test.py'    
            
        }
         stage('teardown'){
            echo 'start end'
        }
    
}
