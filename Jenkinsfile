pipeline { 
    agent any
    stages { 
         stage ("SCM Chkout-1"){ 
              steps { 
                   git 'https://github.com/Gowtham-GitHub/java-project' 
              } 
         } 
         stage ("java execute"){ 
              steps { 
                   sh label: '', script: '''javac *.java java Simple''' 
              } 
         } 
    } 
}
