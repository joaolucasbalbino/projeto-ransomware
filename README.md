# Projeto Ransomware

## Sobre o Desafio

Este projeto tem como objetivo **implementar um Ransomware para criptografar arquivos utilizando a linguagem Python**.

**Arquivos do projeto:**

* [encrypter](encrypter.py): código que irá criptografar os arquivos;
* [descrypter](decrypter.py): código que irá descriptografar um arquivo previamente criptografado.

## Descrição sobre o desafio

A propósito do projeto é capturar um arquivvo em formato de texto e usando um código Python encriptar o que está escrito dentro do arquivo, onde se um hacker tentar extrair este arquivo para fins maliciosos não saiba o conteudo do arquivo. Para ter acesso a este conteudo ele teria que ter uma chave especifica para conseguir descriptografar o conteudo.

Para este projeto vamos criar o encriptador e o descriptador, usaremos duas bibliotecas para este projeto: ***os*** *(identificar o tipo de sistema operacional)* e a ***pyaes*** *(fazer a criptografar e descriptografar)*

Usaremos algumas variaveis para abrir e fechar o arquivo *.txt* e fazer toda a tratativa dos dois arquivos, nests caso vamos criar um arquivo ***teste.txt*** com um conteudo nele.

Para rodar estes arquivos é preciso ter acesso ao terminal do linux ou um WSL se estiver usando windows
