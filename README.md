# Calculadora de Média Escolar com PyQt6

## Descrição

Este projeto consiste em uma aplicação desktop desenvolvida em Python utilizando a biblioteca PyQt6. O sistema permite calcular a média escolar de um aluno com base em três notas informadas pelo usuário, exibindo automaticamente a situação acadêmica de acordo com o resultado obtido.

A interface gráfica foi criada com o Qt Designer e integrada ao código Python, proporcionando uma experiência simples e intuitiva para o usuário.

## Funcionalidades

* Cadastro do nome do aluno;
* Inserção de três notas;
* Cálculo automático da média aritmética;
* Exibição da situação do aluno;
* Limpeza dos campos por meio de um botão específico;
* Tratamento de erros para entradas inválidas.

## Tecnologias Utilizadas

* Python 3
* PyQt6
* Qt Designer
* Programação Orientada a Eventos

## Objetivo do Projeto

O objetivo deste projeto é aplicar conceitos de desenvolvimento de interfaces gráficas em Python, utilizando componentes visuais e lógica de programação para automatizar o cálculo de médias escolares.

Além disso, o sistema auxilia na prática de conceitos como:

* Variáveis e operadores matemáticos;
* Estruturas condicionais (`if`, `elif`);
* Funções;
* Tratamento de exceções (`try` e `except`);
* Manipulação de widgets;
* Eventos de clique em botões.

## Como Funciona

O usuário informa o nome do aluno e suas três notas. Ao clicar no botão **Calcular**, o sistema calcula a média aritmética das notas e apresenta o resultado na tela juntamente com a situação acadêmica correspondente.

### Critérios de Avaliação

* Média maior que 7: Aprovado(a);
* Média entre 5 e 7: Necessita Recuperação;
* Média abaixo de 4: Reprovado(a).

Caso sejam digitados valores inválidos, o sistema exibe uma mensagem de erro orientando o usuário a informar apenas números.

## Aprendizados

Durante o desenvolvimento deste projeto foram trabalhados conceitos importantes como:

* Desenvolvimento de aplicações desktop;
* Criação de interfaces gráficas com PyQt6;
* Manipulação de componentes visuais;
* Cálculos matemáticos;
* Estruturas de decisão;
* Tratamento de erros;
* Organização de código em funções.

## Melhorias Futuras

* Exibir o nome do aluno no resultado;
* Ajustar automaticamente os critérios de recuperação;
* Histórico de alunos avaliados;
* Salvamento dos resultados em arquivo;
* Interface mais moderna e personalizada;
* Geração de boletins em PDF.

Este projeto foi desenvolvido com finalidade educacional e demonstra a utilização do Python e do PyQt6 na criação de sistemas acadêmicos simples para cálculo e acompanhamento do desempenho escolar.
