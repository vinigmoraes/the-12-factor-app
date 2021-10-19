# Dependencies / Dependências

Declarar de forma explicita e isolar as dependencias

Durante o desenvolvimento de uma aplicação normalmente temos algumas necessidades como enviar email, SMS entre outros, ao invés de implementar todo um recurso para fazer esse tipo de ação, podemos simplesmente baixar recursos na web que já tenham implementado esse tipo de recurso como por exemplo SDK.

### Isolando a utilização de dependencias

É importante que a utilização de dependencias seja isolada pois assim, conseguimos abstrair a utilização dessa dependencia sem afetar o nosso código diretamente, como por exemplo criando interfaces no qual nossas classes abstratas podem implementar utilizando a dependencia desejada. 

### Gerenciador de dependencia

Abaixo exemplos de gerenciadores de dependencias:

- Gradle
- NPM
- Pip