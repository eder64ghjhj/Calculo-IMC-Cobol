# Calculadora de IMC em COBOL 🚀

Este projeto é um utilitário simples desenvolvido em COBOL para calcular o Índice de Massa Corporal (IMC). 

## 💻 Sobre o Código
O programa solicita a entrada de peso e altura, processa o cálculo matemático e exibe o resultado formatado na tela. 

### 🛠️ Desenvolvimento e Verbos Utilizados
O código foi estruturado seguindo as divisões padrão da linguagem e utiliza os seguintes comandos técnicos:

* **IDENTIFICATION & DATA DIVISION:** Organização do programa e declaração de variáveis.
* **PIC (Picture Clause):** Definição de tipos de dados (numéricos e decimais).
* **ACCEPT & DISPLAY:** Comandos para entrada de dados do usuário e exibição de mensagens.
* **COMPUTE:** Utilização deste verbo para realizar o cálculo matemático: `PESO / (ALTURA * ALTURA)`.
* **STOP RUN:** Comando para encerrar a execução do programa com segurança.

### 🔍 Validação do Ambiente
Devido a particularidades de ambiente local no Windows (bibliotecas GMP), a execução e a lógica foram validadas e testadas com sucesso via compilador online (**JDoodle**).

## 🚀 Como Executar
1. Copie o conteúdo do arquivo `IMC.cbl`.
2. Utilize um compilador COBOL (local ou online) para processar o arquivo.
3. Insira os dados conforme solicitado pelo programa (Ex: Altura 175 para 1.75m).
