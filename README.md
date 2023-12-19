# Teste Lexter.ai

## Introdução

O teste consiste em escrever um algoritmo que modifique uma lista de objetos do tipo **Input** (definido em `src/input.py`) para uma lista de objetos do tipo **Output** (definido em `src/output.py`), usando Python e quaisquer outras ferramentas que deseje.

Faça um fork do projeto, desenvolva, `commit` e `push` para compartilhar conosco.

## Objetivo

### Principal

Entender as estruturas de dados (**Input** e **Output**) e desenvolver o algoritmo descrito na introdução acima.

## Observações Gerais

* O arquivo de entrada do projeto é o `src/main.py`;
* Não é obrigatória e nem proibida a utilização de nenhuma biblioteca específica.
* Atividade secundária: Caso haja tempo habil, criar testes e cenários para validação do algoritmo será um bônus.
* Qualidade e estruturação do código também serão avaliados.

## Detalhes Sobre o Modelo de Dados

* Todos os níveis da lista de output devem estar em ordem crescente por `entryId`;
* Uma entrada deve ser filha da outra se o início do `path` de ambas for igual, ou seja, a entrada 'root/path' é filha da entrada 'root';
* A estrutura tem profundidade indefinida;
* A chave `fullPath` do Output é uma string com todos os elementos do `path` separados por `/`;
* A chave `currentPath` é o valor do `path` atual. Ou seja, para a entrada de `fullPath` `root/path`, o seu `currentPath` é `path`;
* Os arquivos `src/input.py` e `src/output.py` têm um exemplo de um array de input e um de output.