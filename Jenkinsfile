pipeline{
  agente any
  stages{
    stage ('Build Backend'){
      steps {
        bat 'mvn clean package -DskipTests=true'
      }
    }
  }
}
