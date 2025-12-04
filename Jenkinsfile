pipeline {
  agent any
  stages('build'){
    steps{
      sh 'mvn clean package -DskipTests'
    }
    
  }
}
