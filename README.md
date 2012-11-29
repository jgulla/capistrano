Introduction to Capistrano 
==========

Here are the slides and notes from my talk about capistrano, given at Rich Web 2012

# Create a rails project without a database:
rails new capdemo -O

# Create a simple webapp via Maven:
mvn archetype:generate -DgroupId=rwx.cap -DartifactId=capid -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false

# Java option to use /dev/urandom instead of /dev/random
export JAVA_OPTS=-Djava.security.egd=file:/dev/./urandom
See (http://tomcat.10.n6.nabble.com/Hanging-on-startup-td4571254.html)
and (http://stackoverflow.com/questions/137212/how-to-solve-performance-problem-with-java-securerandom)


