node()
{
stage('checkout')
{
checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/ajith26061995/Demo.git']]])
}
stage('listing files')
{
sh "ls -latr"
}}