pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                     echo 'Hi, this is Zulaikha from edureka'
                 }
                 }

                 stage('showing helloworld') {
                 steps {
                     cat ./helloworld.txt
                 }
                 }
         
                //  stage('Four') {
                //  parallel { 
                //             stage('Unit Test') {
                //            steps {
                //                 echo "Running the unit test..."
                //            }
                //            }
                //             stage('Integration test') {
                //               agent {
                //                     docker {
                //                             reuseNode true
                //                             image 'ubuntu'
                //                            }
                //                     }
                //               steps {
                //                 echo "Running the integration test..."
                //               }
                //            }
                //            }
                // }
              }
}
