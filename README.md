# Feature Selection com Probe Method

Um exemplo prático do **Método Probe** para seleção de variáveis em problemas de Machine Learning. Este repositório acompanha o post de LinkedIn “Feature Selection with the Probe Method” e traz todo o código e notebooks necessários para reproduzir a análise.

---

## 📋 Sumário

1. [Sobre o Projeto](#sobre-o-projeto)  
2. [Instalação](#instalação)  
3. [Estrutura do Repositório](#estrutura-do-repositório)  
4. [Como Executar](#como-executar)  
5. [Metodologia: Método Probe](#metodologia-método-probe)  
6. [Exemplo de Resultados](#exemplo-de-resultados)  
7. [Contribuindo](#contribuindo)  
8. [Licença](#licença)  

---

## Sobre o Projeto

A seleção de variáveis (feature selection) é etapa crítica para melhorar a interpretabilidade, reduzir overfitting e acelerar o treinamento de modelos. O **Método Probe** consiste em:

1. Adicionar uma variável aleatória (“probe”) ao dataset.  
2. Treinar um modelo de ML (ex.: RandomForest).  
3. Calcular importâncias das variáveis.  
4. Descartar todas as variáveis reais que ficarem abaixo da random probe.  
5. Repetir até convergir.

Este notebook demonstra, passo a passo, como aplicar o método a um conjunto de dados de exemplo.

---

## Instalação

1. **Clone o repositório**  
   ```bash
   git clone https://github.com/raulward/feature_selection_probe_method.git
   cd feature_selection_probe_method
