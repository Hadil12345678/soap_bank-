# SOAP Lab Answers

## XSD Role
The XSD defines the SOAP contract and XML message structure.

## Namespace
http://example.com/bank

## Operations
- GetAccount
- Deposit
- Withdraw

## Endpoint
http://localhost:8080/ws

## Added Feature
Withdraw operation.

## Modified Files
- bank.xsd
- BankEndpoint.java

## Tests Done
- GetAccount success
- Deposit success
- Withdraw success
- SOAP Fault success