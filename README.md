
API para armazenamento de heróis utilizando Spring WebFlux.


Neste projeto é implementada uma api de armazenamento de heróis, utilizando-se das seguinte tecnologias:

- Java 8
- Sprinpg data
- Spring WebFlux
- JUnit
- sl4j
- reactor
- DynamoDB
- AWS Cli

Os dados foram persistidos no bando de dados DynamoDb, que é noSql, numa instalação local e foi acessado por meio do aws cli.


Para iniciar o servidor Dynamo, basta executar o comando abaixo: 

 java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
 
E depois para acessá-lo:
 
 aws dynamodb list-tables --endpoint-url http://localhost:8000

