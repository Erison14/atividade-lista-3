# atividade-lista-3 

# Atividade Prática: Manipulação de Arquivos no Linux

Este documento contém as soluções para a atividade focada em administração de sistemas e manipulação de texto no terminal Linux.

## Sobre a Atividade
O objetivo foi resolver problemas de administração de sistema usando apenas a linha de comando, sem interface gráfica. Os exercícios focam em extrair e filtrar informações de arquivos do sistema.

## Comandos Utilizados
As soluções foram construídas utilizando o encadeamento de comandos (pipes `|`) com as seguintes ferramentas:
* **grep:** Busca de padrões e palavras em textos.
* **sed:** Filtragem e extração de linhas e campos.
* **cut:** Recorte de colunas específicas.
* **wc:** Contagem de linhas.
* **sort e head:** Ordenação aleatória e limitação de exibição.

## Resumo das Questões
* **Questão 1:** Leitura do arquivo `/proc/cpuinfo` para contar o número de processadores.
* **Questão 2:** Exploração do arquivo `/etc/passwd` para listar e contar usuários com acesso ao shell, usuários de sistema e total de grupos.
* **Questão 3:** Criação e manipulação do arquivo `mypasswd` para extrair nomes completos de usuários pertencentes ao grupo 1000.
* **Questão 4:** Criação de um comando único para sortear aleatoriamente o primeiro nome de um funcionário do setor "Main Office".

## Como executar
Os comandos podem ser executados em qualquer terminal Linux. 

Para testar as questões 3 e 4 corretamente, é necessário criar a cópia local do arquivo de senhas antes de rodar os comandos:
cp /etc/passwd mypasswd
