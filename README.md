

## Create a sonar-cens-report 

### Download the Tool:
- Ensure you have the sonar-cnes-report-4.2.0.jar file downloaded to your local machine.
- Link: https://github.com/cnescatlab/sonar-cnes-report/releases

### Run the Command:

- java -jar <path of jar file> -s <SonarQube_URL> -t <User_Token> -p <Project_Key> -o <Output_File>

### Replace the placeholders with the following information:
- <SonarQube_URL>: The URL of your SonarQube server 
- <User_Token>: Your user token from sonarQube (my account -> security -> token)
- <Project_Key>: The key of the SonarQube project for which you want to generate the report 
- <Output_File>: The desired name for the output file 

