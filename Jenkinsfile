pipeline
{
  agent any
  tools
  {
    jdk "Default"
  }
  stages{
  stage("Build")
  {
    steps
    {
      bat "javac Hello.java"
    }
  }
  stage("Run")
  {
    steps
    {
      bat "java Hello"
    }
  }
  }
}
