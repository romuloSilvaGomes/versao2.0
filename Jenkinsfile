pipeline {
  
  agent any 
  parameters {
    
   string(name: 'STATEMENT', defaultValue: 'hello; ls /', description: 'What should I say?') 
    
  }
    stages {
          stage ('INICIANDO PIPELINE'){
           
                 steps('INICIO DO STEP'){
                    
                  sh('echo ${STATEMENT}')
                 }
          }
      }
  
}
