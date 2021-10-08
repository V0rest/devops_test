pipeline {
  agent any
  
    stages {
      
        stage('JenkinsBuild') {
            steps {
                echo "start"
              get_file = new URL ("https://raw.githubusercontent.com/Vorest35/devops_test/d04ab03e2baaf79c6a8135078f23640ec409d29e/readme.txt").getText()
writeFile(file: 'readme.txt', text: file_text)
              /*new URL ("https://raw.githubusercontent.com/Vorest35/devops_test/d04ab03e2baaf79c6a8135078f23640ec409d29e/readme.txt").getText()*/
              sh cat "readme.txt"
              
              
              
               /*new File("readme.txt") << new URL ("https://raw.githubusercontent.com/Vorest35/devops_test/d04ab03e2baaf79c6a8135078f23640ec409d29e/readme.txt").getText()*/
              
              /*
              file = new URL ("https://raw.githubusercontent.com/Vorest35/devops_test/d04ab03e2baaf79c6a8135078f23640ec409d29e/readme.txt").getText()
writeFile(file: 'readme.txt', text: file_text)*/
              /*
             writeFile(file: 'readme.txt', text: main_text)
sh("echo '${main_text}'" >> readme.txt)*/
               /*echo "Soon I will be a DevOps engineer"*/
                echo "end"
            }
        }
    }
}
                        
