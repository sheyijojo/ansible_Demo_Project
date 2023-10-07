pipeline{
  agent any  
  stages{  
      stage("Run ansible playbook"){
        steps{
        ansiblePlaybook credentialsId: 'cloudconvokey', inventory: 'hosts', playbook: 'nginx_install.yaml'
        }
      }
  }
}
