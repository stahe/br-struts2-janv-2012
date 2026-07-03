# Introdução ao framework Struts 2 com exemplos (2012)

🔗 **Curso on-line:**
[https://stahe.github.io/br-struts2-janv-2012/](https://stahe.github.io/br-struts2-janv-2012/)

---

## Visão geral

Este documento oferece uma **introdução ao framework Struts 2** por meio de uma abordagem passo a passo baseada em exemplos.

O Struts 2 é um framework web em Java que oferece o seguinte:

* um conjunto de bibliotecas distribuídas na forma de arquivos **JAR**
* uma estrutura de desenvolvimento que oferece orientação na concepção de uma aplicação web

O objetivo é compreender os conceitos básicos do Struts 2 na prática.

---

## Requisitos

Para acompanhar os exemplos, é necessário o seguinte:

* conhecimentos básicos de **Java**
* conhecimentos básicos de **desenvolvimento web**, especialmente **HTML**

Recursos adicionais estão disponíveis em:

* [http://developpez.com](http://developpez.com)

---

## Referências para aprofundamento

Para mais informações:

* **[ref1]** Documentação oficial do Struts 2 (site oficial do projeto)
* **[ref2]** *Struts 2 in Action*
  Donald Brown – Chad Michael Davis – Scott Stanlick
  Manning Publishing

Neste documento, há referências ocasionais ao livro *Struts 2 in Action* para explicar melhor determinados aspectos técnicos.

---

## Objetivo de aprendizagem

O documento foi elaborado de forma a poder ser lido sem a necessidade de um computador.
Foram incluídas inúmeras capturas de tela para facilitar a compreensão.

---

## O papel do Struts 2 em uma aplicação web

O Struts 2 está presente **exclusivamente na camada web** de uma arquitetura multicamadas típica.

### Arquitetura geral

Uma aplicação web clássica pode ser estruturada da seguinte forma:

### 1️⃣ Camada web

* Interface com o usuário (navegador)
* Processamento de solicitações HTTP
* Geração de respostas
* **O Struts 2 está exclusivamente nesta camada**

### 2️⃣ Camada de negócios

* Implementa as regras de negócios
* Exemplo: cálculo de um salário, geração de uma fatura
* Utiliza:

  * dados da camada web
  * dados do banco de dados por meio da camada DAO

### 3️⃣ Camada DAO/JPA/JDBC

* Gerenciamento do acesso aos dados
* DAO: Objetos de Acesso a Dados
* JPA: Java Persistence API
* JDBC: acesso de baixo nível ao banco de dados
* O JPA atua como ORM (Mapeador Objeto-Relacional)

### 4️⃣ Integração das camadas

Pode ser realizada por:

* **Spring**
* **EJB3 (Enterprise Java Bean)**

---

## Estrutura dos exemplos

A maioria dos exemplos neste documento **utiliza exclusivamente a camada web** para enfatizar o Struts 2.

No final do documento, será construída uma **aplicação web completa com várias camadas**:

* Camada web
* Camada de negócios
* Camada DAO
* Camada JPA/Hibernate
* Acesso ao banco de dados via JDBC

As camadas de negócios e de persistência são fornecidas na forma de um arquivo JAR, para que o leitor possa se concentrar principalmente na camada web.

---

## Público-alvo

* Desenvolvedores Java que desejam conhecer o Struts 2
* Estudantes de desenvolvimento web em Java
* Qualquer pessoa que queira compreender a integração do Struts 2 em uma arquitetura multicamadas

---

## Autor

Serge Tahé, Versão 2012

---
