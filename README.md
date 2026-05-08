# Introdução ao SQL com o SGBD Firebird

➡️ Curso relacionado: **[Introdução ao SQL com o SGBD Firebird](https://stahe.github.io/pt-sql-firebird-janv-2006/)**

## Resumo

Este documento é uma introdução à linguagem **SQL (Structured Query Language)** tal como se aplica ao **sistema de gestão de bases de dados Firebird**.
Revê e adapta um documento educativo anterior escrito em **1991 para a Oracle**, que por sua vez se inspirou em grande medida na documentação oficial da Oracle e no livro:

* *SQL – Introdução, programação e domínio*
  de **Christian Marée** e **Guy Ledant**, publicado pela Eyrolles. 

O SQL é uma **linguagem padrão utilizada para criar, manter e consultar bases de dados relacionais**.
É em grande medida independente do sistema de gestão de bases de dados (SGBD) utilizado, embora alguns SGBD introduzam extensões próprias. 

## Porquê o Firebird?

Os exemplos deste documento utilizam o **SGBD Firebird**.
Esta escolha deve-se a uma característica que se revela especialmente prática num contexto educativo: uma base de dados Firebird pode **ser contida num único ficheiro**.

Isto permite, por exemplo:

* copiar facilmente uma base de dados para uma **pen USB**
* utilizá-la em **diferentes computadores** (em casa, na universidade, no laboratório)
* trabalhar sem uma infraestrutura complexa

## Compatibilidade com SQL

Embora os exemplos tenham sido escritos para o Firebird, a maioria pode ser reproduzida com outros SGBDs relacionais, por exemplo:

* MySQL
* PostgreSQL
* Firebird
* SQL Server Express
* Microsoft Access
* Oracle

Todos estes sistemas utilizam SQL, por vezes com **variantes ou extensões específicas do produto**.

## Público-alvo

Este documento destina-se a:

* **principiantes que desejam aprender SQL**
* pessoas que desejam **revisar os conceitos básicos da linguagem**

Centra-se na aprendizagem do **SQL fundamental**.

## Exclusões do âmbito de aplicação

Existem certos tópicos que foram omitidos intencionalmente:

* procedimentos armazenados
* programação avançada em SQL
* API do SQL
* administração de SGBD

O objetivo é oferecer uma **introdução clara e passo a passo à linguagem SQL**.

Serge Tahé, janeiro de 2006