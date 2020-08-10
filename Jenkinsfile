node{
    stage('1 git the source'){
    git 'https://github.com/davidding2020/githellowworld'
    }

     stage ('2 compile package'){
     def mvnHome = tool name: 'maven-3' type 'maven'    
         sh "{mvnHome}/bin/mvn package"
     }
}
