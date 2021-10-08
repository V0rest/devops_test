pipeline {
  agent any
  
    stages {
      
        stage('JenkinsBuild') {
            steps {
                echo "start"
              file_text = new URL ("https://github.com/Vorest35/devops_test/blob/d04ab03e2baaf79c6a8135078f23640ec409d29e/readme.txt").getText()
writeFile(file: 'readme.txt', text: file_text)
              /*writeFile(file: 'readme.txt', text: main_text)
sh("echo '${main_text}' >> readme.txt)*/
               /*echo "Soon I will be a DevOps engineer"*/
                echo "end"
            }
        }
    }
}
                        
