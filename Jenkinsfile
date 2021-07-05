pipeline{
   agent any 
   stages{
      stage("Execute ansible"){
          steps{
                 ansiblePlaybook credentialsId: 'ansible-user', disableHostKeyChecking: true, installation: 'ansible', inventory: 'Inventory.inv', playbook: 'tomcat.json'
               }
                           }
       }
  }   
