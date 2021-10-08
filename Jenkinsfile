pipeline {
  agent any
  
    stages {
      
        stage('JenkinsBuild') {
            steps {
                echo "start"
              writeFile(file: 'readme.txt', text: main_text)
sh("echo '${main_text}' >> readme.txt)
               /*echo "Soon I will be a DevOps engineer"*/
                echo "end"
            }
        }
    }
}
                        
