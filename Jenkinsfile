pipeline{
  agent any
  stages{
    stage ('Build Backend'){
      steps {
        bat 'mvn clean package -DskipTests=true'
      }
    }
    stage ('unit Test'){
      steps {
        bat 'mvn test'
      }
    }
  }
}
