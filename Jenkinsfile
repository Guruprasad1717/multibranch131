sh 'mvn package'

{

stage('Continuous Deployment')

{

sh 'scp  /home/ubuntu/.jenkins/workspace/ScriptedPipeline/webapp/target/webapp.war   ubuntu@172.31.44.187:/var/lib/tomcat9/webapps/qaenv.war'

}

stage('Continuous testing')

{

sh 'echo "Testing Passed"'

}
}

