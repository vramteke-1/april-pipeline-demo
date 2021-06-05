pipeline
{
agent any
stages
{ stage ('sch checkout')
  {  steps { sh 'echo code_is_downloading'} }

  stage('please build the code')
  { steps {  sh 'echo code_is_building' } }
}
}
