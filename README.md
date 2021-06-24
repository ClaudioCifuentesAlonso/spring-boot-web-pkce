# spring-boot-web-pkce
Demo project for Spring Boot and OAuth 2.0 PKCE in a JavaScript application

## Usage

This application uses OAuth2.0, and it has dependencies:
1. Authorization server running on port 8080 and configured it. Here we have the configuration instructions using [Keycloak](https://claudiocifuentes.atlassian.net/l/c/1rhvGugs)
2. API Gateway running on port 8082, here is the [API Gateway application repository](https://claudiocifuentes.atlassian.net/l/c/1rhvGugs).
3. Simple Resource server running, here is the [Spring Boot Resource Server repository](https://github.com/ClaudioCifuentesAlonso/oauth2.0-spring-cloud-apigateway.git).

To run this application once all the dependencies are running:

```
mvn spring-boot:run
```