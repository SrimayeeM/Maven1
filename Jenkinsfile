pipeline{
agent any
stages{
stage("Cleaning Stage")
{
  steps{
bat label: '', script: 'bat "mvn clean"'
  }}
stage("Testing Stage")
  { steps{
bat label: '', script: 'bat "mvn test"'
  }}
stage("Packaging Stage"){
steps{ 
bat label: '', script: 'bat "mvn package"'
}
}
}
}
