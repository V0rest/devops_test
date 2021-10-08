pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M3"
    }
    stages {
      
        stage('JenkinsBuild') {
            steps {
                echo "start"
                 url = "https://raw.githubusercontent.com/Vorest35/devops_test/d04ab03e2baaf79c6a8135078f23640ec409d29e/readme.txt".toURL()
        result = getToString(url.getText())
        echo "${result}"
                /*
               script {
                 
              sh echo https://raw.githubusercontent.com/Vorest35/devops_test/d04ab03e2baaf79c6a8135078f23640ec409d29e/readme.txt */
                 /*
                 new File("readme.txt") << new URL ("https://raw.githubusercontent.com/Vorest35/devops_test/d04ab03e2baaf79c6a8135078f23640ec409d29e/readme.txt").getText()
                 println file.text
                 */
                 /*
                def data = httpRequest 'https:/raw.githubusercontent.com/Vorest35/devops_test/cce7e6e4a76b9467532c78fa624a358f4bc7dd50/readme.txt'
                  println(data)
                  */
                 /*
                   def data = readFile(file: 'https://raw.githubusercontent.com/Vorest35/devops_test/cce7e6e4a76b9467532c78fa624a358f4bc7dd50/readme.txt')
                   println(data)
         */
          
              
              
              
              /*
              new File("readme.txt") << new URL ("https://raw.githubusercontent.com/Vorest35/devops_test/cce7e6e4a76b9467532c78fa624a358f4bc7dd50/readme.txt").getText()
              */
              
              /*
              get_file = new URL "https://raw.githubusercontent.com/Vorest35/devops_test/d04ab03e2baaf79c6a8135078f23640ec409d29e/readme.txt" ).getText()
writeFile(file: 'readme.txt', text: file_text)*/
              /*new URL ("https://raw.githubusercontent.com/Vorest35/devops_test/d04ab03e2baaf79c6a8135078f23640ec409d29e/readme.txt").getText()*/
             /* sh cat "readme.txt"*/
              
              
              
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
                      
