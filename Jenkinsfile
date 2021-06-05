pipeline
{
agent any
stages
{ stage ('sch checkout')
  {  steps { sh 'echo code_is_downloading'} }

  stage('please build the code')
  { steps {  sh 'echo code_is_building' } }
 
 stage('please deploy the code on dev')
  { steps {  sh 'echo code_is_deploying' } }
 
 stage('please deploy the code on QA')
  { steps {  sh 'echo code_is_deploying' } }
}
}
}
}
