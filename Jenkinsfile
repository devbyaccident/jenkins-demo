pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "$GIT_BRANCH"
         }
      }
      stage('Feature') {
         steps {
            echo "This feature is really awesome!"
         }
      }
   }
}
