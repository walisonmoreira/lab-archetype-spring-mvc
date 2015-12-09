# Lab Archetype Spring MVC

## Como Usar

Para criar um projeto no modo interativo:

`mvn archetype:generate -DarchetypeGroupId=lab -DarchetypeArtifactId=lab-archetype-spring-mvc -DarchetypeVersion=0.0.1-SNAPSHOT`

Para criar um projeto com groupId=**lab**,  artifactId=**lab-temp**, version=**0.0.1-SNAPSHOT** e package=**lab** com um único comando:

`mvn archetype:generate -DarchetypeGroupId=lab -DarchetypeArtifactId=lab-archetype-spring-mvc -DarchetypeVersion=0.0.1-SNAPSHOT -DgroupId=lab -DartifactId=lab-temp -Dversion=0.0.1-SNAPSHOT -Dpackage=lab -DinteractiveMode=false`

## Como Foi Criado

Para criar o archetype inicial:

`mvn archetype:generate -DarchetypeArtifactId=maven-archetype-archetype -DgroupId=lab -DartifactId=lab-archetype-spring-mvc -Dversion=0.0.1-SNAPSHOT -Dpackage=lab -DinteractiveMode=false`

### Fontes de Pesquisa

Documentações utilizadas para criar o archetype:

* [Introduction to Archetypes](https://maven.apache.org/guides/introduction/introduction-to-archetypes.html)
* [Guide to Creating Archetypes](https://maven.apache.org/guides/mini/guide-creating-archetypes.html)
* [Criando um archetype no maven](http://blog.camilolopes.com.br/criando-um-archetype-no-maven/)
