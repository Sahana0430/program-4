Pipeline
 {
 agent any tools
 {
 maven 'Maven-3' 
} 
Stages
 {
 stage('Checkout') {
 steps { 
git branch: 'main', url: ‘https://github.com/Sahana0430/program-4’
} 
}
 stage('Build') { 
steps { sh 'mvn clean compile' } 
} 
stage('Test') {
 steps { sh 'mvn test' }
 } 
stage('Package') { 
steps { sh 'mvn package' } 
}
           }
          }
