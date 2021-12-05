pipeline{
    agent {
  label 'node1'
}

    stages {
        stage('build') {
        steps {
            echo 'running build automation'
            sh './gradlew build --no-daemon'
            archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            
        }
        
            
        }
        
        
        
    }
    
}
