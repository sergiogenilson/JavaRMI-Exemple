# Exemplo de uso de Java RMI

Exemplo de aula

## Compilando o projeto

Em um terminal execute:
```bash
javac HelloInterface.java HelloServer.java HelloClient.java
```

## Como executar o exemplo

Em um terminal rode o seguinte comando para rodar o RMI Registry:

``` bash
rmiregistry
```
Em outro terminal rode o Servidor:

```bash
java HelloServer
```

E em outro terminal rode o Cliente:

```bash
java HelloClient
```