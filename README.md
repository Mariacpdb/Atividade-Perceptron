# 🧠 Perceptron – Atividade Prática de Inteligência Artificial  

## 📘 Descrição da Atividade  
Este repositório contém a atividade prática da disciplina de Inteligência Artificial, cujo objetivo é compreender, de forma aplicada, o funcionamento do Perceptron — um dos modelos mais simples e fundamentais de redes neurais artificiais.  

## 🎯 Objetivos  
- Reproduzir e executar o código do Perceptron.  
- Versionar o código em repositório GitHub.  
- Responder às perguntas propostas sobre o modelo e seu funcionamento.  

## 📂 Estrutura do Repositório  
- `perceptron.py`: código em Python do Perceptron.  
- `README.md`: explicação e respostas às perguntas.  

---

## 📌 Perguntas e Respostas  

### 1. Conceito  

Explique, com suas palavras, o que é um Perceptron e qual a sua importância histórica para o
desenvolvimento da Inteligência Artificial.

O **Perceptron** é um modelo de rede neural artificial criado por Frank Rosenblatt em 1958. Ele funciona como um "neurônio artificial" que recebe entradas, aplica pesos, soma os valores, adiciona um viés (bias) e, por meio de uma função de ativação, gera uma saída.  
Historicamente, foi o primeiro passo importante para o desenvolvimento da Inteligência Artificial e inspirou as arquiteturas de redes neurais modernas.  

### 2. Funcionamento  
O Perceptron é considerado um **classificador linear**, pois ele só consegue separar dados que podem ser divididos por uma linha (ou hiperplano em dimensões maiores).  
- Isso significa que ele é eficiente para problemas **linearmente separáveis**, como AND e OR.  
- Porém, ele não consegue resolver problemas mais complexos, como a porta lógica **XOR**, que exige modelos com múltiplas camadas (redes neurais profundas).  

### 3. Código  
As principais etapas do processo de treinamento do Perceptron são:  
1. Inicialização dos pesos e do bias (geralmente com valores aleatórios ou zero).  
2. Cálculo da saída: soma ponderada das entradas + bias → função de ativação.  
3. Comparação com a saída esperada (erro).  
4. Atualização dos pesos e bias com base no erro (regra de aprendizado).  
5. Repetição do processo até que o erro seja minimizado ou atinja um número de épocas definido.  

### 4. Aplicação prática  
Um exemplo real em que o Perceptron pode ser útil é na **classificação de e-mails como spam ou não spam**.  
Apesar de existirem modelos muito mais avançados hoje, o Perceptron pode servir como uma solução inicial para problemas simples de classificação binária. Ele é rápido, fácil de implementar e permite entender os conceitos fundamentais de aprendizado supervisionado.  

---
