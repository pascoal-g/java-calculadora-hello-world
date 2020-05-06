# java-calculadora-hello-world
FIAP 2DVP - Microservices


## Gerar o projeto com SpringBoot
[start.spring.io](https://start.spring.io/)

## Configure seu projeto:
```
Project: Maven Project
Language: Java
Spring Boot: 2.2.4
Project Metada: fiap.aula1
Artifact: calculadoraRest
No item Dependencies, adicione as seguintes dependências:
Spring Web (dentro do menu Web)
Spring Boot Actuator (dentro do menu Ops)
```
Clique em Generate, isso irá baixar o projeto no formato ZIP.

## Instale o plugin Maven for Java para o VsCode

[vscode-maven](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven)


## Iniciando o projeto

1. Baixe o projeto .zip no seu workspace e descompacte-o

```
$ unzip calculadoraRest.zip
```

2. Abra o VsCode no diretorio descompactado
```
$ code calculadoraRest
```

3. Instale as dependencias do maven no VsCode:

Abra o executor de comandos do code com <kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> e navegue:
```
> Maven: Execute Commands > calculadoraRest > clean
> Maven: Execute Commands > calculadoraRest > install
```

4. Adicione a classe Calculadora Controller no projeto

5. Para rodar chame novamente o executor de comandos <kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
```
> Run and Debug 
```

## Testando

``` 
curl http://localhost:8080/v1/calculadora/somar/10/20
```

