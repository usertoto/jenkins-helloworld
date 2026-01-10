node {
    
    stages{
        stage('clone'){
           
                sh 'rm -rf *'
                sh 'git clone https://github.com/usertoto/jenkins-helloworld.git'
            
        }
        stage('build'){
      
            sh 'cd jenkins-helloworld/ && javac Main.java'
        }
          
        stage('run'){
       
            sh 'cd jenkins-helloworld/ && java Main'
        
        } 
    }
    
    
}
