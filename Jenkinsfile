pipeline {
     agent any
     stages {
         tidy -q -e *.html
         stage('Upload to AWS') {
             steps {
                 sh 'echo "Hello Wolrd"'
                 sh '''
                     echo "Multiline shell steps works too"
                     ls -lah
                 '''
             }
         }
     }
}
