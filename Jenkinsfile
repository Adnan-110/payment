@Library('Jenkins-Shared-Library') _ 
// def SONAR_URL="172.31.39.131"
// def component="Payment"
// maven(component,SONAR_URL)
// There is another way to perform same action where we dont have to pass and catch value 
// Simply declare environment variable like below
env.COMPONENT="Payment"
env.APP_TYPE="python"
env.SONAR_URL="172.31.39.131"
env.NEXUS_URL="172.31.86.85"
python()

// To see further use check maven and helloWorld file in shared library