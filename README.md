# Previsão de Lucros para Empresas 🧮📈

Este é um projeto desenvolvido para **prever lucros com base no número de funcionários e tempo de operação** de uma empresa. Ele utiliza **regressão linear** e apresenta os dados de forma visual e interativa por meio de uma interface gráfica criada com **Tkinter**.

---

## 📋 Descrição do Projeto

A aplicação permite:
- Visualizar os dados reais de empresas fictícias.
- Prever lucros com base em valores inseridos pelo usuário.
- Exibir um gráfico de regressão com os dados e a previsão.
- Utilizar uma interface simples e intuitiva, com botões para navegar entre funcionalidades.

A regressão linear é aplicada sobre dois fatores: número de funcionários e tempo de operação da empresa, com base em um conjunto de dados simulados.

---

## 🚀 Funcionalidades

1. **Exibir Dados Reais**  
   Mostra uma lista com o número de funcionários, tempo de operação e lucro atual de empresas simuladas.

2. **Previsão de Lucro**  
   O usuário insere os dados de sua empresa (funcionários e tempo de operação) e recebe a previsão do lucro, com exibição gráfica.

3. **Gráfico de Regressão**  
   Um gráfico com os dados reais, a linha de regressão ajustada e a previsão do lucro do usuário é gerado com o Matplotlib.

4. **Interface Gráfica com Menu**  
   Tudo é apresentado em uma janela com botões de navegação intuitivos, desenvolvidos com Tkinter.

---

## 🛠️ Tecnologias Utilizadas

- **Python**
- **Tkinter**: Interface gráfica
- **NumPy**: Manipulação de arrays numéricos
- **Scikit-learn**: Regressão Linear
- **Matplotlib**: Gráficos

---


## 📦 Como executar

1. Certifique-se de ter Python 3 instalado.
2. Instale os pacotes necessários:
   ```bash
   pip install numpy scikit-learn matplotlib
