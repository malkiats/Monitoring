# presto CLI  

Installation Guide : https://prestodb.io/docs/current/installation/deployment.html#installing-presto  

CLI: Download presto-cli-0.266.1-executable.jar, rename it to presto, make it executable with chmod +x, then run it:
https://repo1.maven.org/maven2/com/facebook/presto/presto-cli/0.266.1/presto-cli-0.266.1-executable.jar  
./presto --server localhost:8080 --catalog hive --schema default  

Run the CLI with the --help option to see the available options.  

MySQL Connector: https://prestodb.io/docs/current/connector/mysql.html  
