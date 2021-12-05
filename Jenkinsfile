pipeline{
    agent {
  label 'node1'
}

    stages {
        stage('build') {
        steps {
            echo 'running build automation'
            sh './gradlew build --scan'
            archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            
        }
        
            
        }
        
        
        
    }
    
}
