pipeline{
agent any
stages{
stage("Cleaning Stage")
{
  def mvnHome = tool name: 'Maven', type: 'maven'
steps {
bat "mvn clean"
}
}
stage("Testing Stage")
{
  def mvnHome_ = tool name: 'Maven', type: 'maven'
steps{
bat "mvn test"
}
}
stage("Packaging Stage"){
   def mvnHome__ = tool name: 'Maven', type: 'maven'
steps{ 
bat "mvn package"
}
}
}
}
