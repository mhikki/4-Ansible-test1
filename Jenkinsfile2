node{
  
    stage('clone des fichier Ansible') {
        checkout scm        
    }
   stage('Ansible-Lancement du playbook') {
         
        sh 'ansible-playbook -i hosts playbook.yml'
    }
   
}
