pipieline {
      agent any
      parameters {
           string( name : 'Greeting',defaultvalue : 'Hello',description : 'How should I greet the world?')
      }
      stages {
         stage ('Example') {
           steps {
               echo "& { params.Greeting} Welcome to jenkins World!"
           }
         }
      }
}
