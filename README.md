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


O Perceptron foi o primeiro  modelo de rede neural artificial que foi criado em 1958 por Frank Rosenblatt. Ele é como se fosse um neurônio artificial que recebe entradas, aplica pesos, soma os valores, adiciona um viés (bias) e, por meio de uma função de ativação, gera uma saída.  
Foi considerado o primeiro passo importante para o desenvolvimento da Inteligência Artificial e a partir dele surgiram  as arquiteturas de redes neurais modernas.  

### 2. Funcionamento  
O Perceptron é considerado um classificador linear, ou seja  ele só consegue separar dados que podem ser divididos por uma linha, ele finxikna com 2 , 3 ou mais dimensões .  
Ou seja ele é eficiente para problemas linearmente separáveis, como AND e OR.  
Mas, ele não consegue resolver problemas mais complexos, que exige modelos com múltiplas camadas que sao as redes neurais profundas.  

### 3. Código  
As principais etapas do processo de treinamento do Perceptron são:  
1. Inicialização dos pesos e do bias (geralmente com valores aleatórios ou zero).  
2. Cálculo da saída: soma ponderada das entradas + bias → função de ativação.  
3. Comparação com a saída esperada (erro).  
4. Atualização dos pesos e bias com base no erro (regra de aprendizado).  
5. Repetição do processo até que o erro seja minimizado ou atinja um número de épocas definido.  

### 4. Aplicação prática  
Um exemplo real em que o Perceptron pode ser útil é na classificação de e-mails como spam ou não spam.  


---
