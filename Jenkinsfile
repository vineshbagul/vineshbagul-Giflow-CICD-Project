

pip[eline{

agent any

   stage('sonar quality status'){

   agent {

    docker {
      image 'maven'
          }
      }

      step{

        script {
        withSonarQubeEnv(credentialsId: 'sonar-token') {
            // some block
            bash 'mvn clean package sonar:sonar'
        }
        }
        }
        }
       }
      }
