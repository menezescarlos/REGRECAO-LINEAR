
---

# 📈 **Relacionando Variáveis**

## 📏 **Melhor Reta**

---

## 📝 **2. Explicando a Reta**

Ajustamos uma reta entre o tamanho do primeiro andar e o preço da casa. Queremos explicar o preço da casa a partir do seu tamanho, por isso dizemos que:

- **Variável explicativa/independente:** Área do primeiro andar

- **Variável resposta/dependente:** Preço da casa

---

## 🔄 **Separando em Treino e Teste**

O conjunto de treinamento é usado para ajustar o modelo, enquanto o conjunto de teste é usado para avaliar seu desempenho em prever preços de casas não vistos durante o treinamento. Isso auxilia na generalização do modelo.

---

## 🔍 **Analisando os Coeficientes**  
*(intensidade, direção e significância)*

- **Intercepto:** O valor esperado do preço da casa quando todas as outras variáveis são zero. Neste caso, quando a área do primeiro andar é zero, o preço esperado da casa é de R$ 145.196,40. Nem sempre temos uma interpretação prática desse número.

- **Efeito individual da área:** R$ 6.833,97. Isso indica que, para cada 1m² adicionado à área do primeiro andar, espera-se que o preço da casa aumente, em média, R$ 6.833,97.

---

## 📊 **Explicabilidade do Modelo**

Quanto a variação da área está explicando os diversos preços das casas?

Nesse caso, recorremos à métrica **R²**, o coeficiente de determinação. O **R²** varia de 0 a 1, onde 1 indica um ajuste perfeito do modelo aos dados, ou seja, todas as variações na variável dependente são explicadas pelas variáveis independentes no modelo. Por outro lado, um **R²** de 0 indica que o modelo não explica nenhuma variabilidade na variável dependente.

---

## 🧮 **Entendendo o Resíduo**

---

## 📈 **Obtendo o R² da Previsão**

---

## ➕ **3. Adicionando Outras Características**

O modelo com apenas um fator nos mostrou um **R²** de 0,37, ou seja, aproximadamente 37% da variação observada nos preços das casas pode ser explicada pela variação na área. Isso indica que ainda há uma quantidade significativa de variação que não está sendo capturada por esse modelo específico. Vamos analisar outros fatores para explicar o preço das casas.

---

## 📊 **Analisando os Fatores**

---

## ➕ **Adicionando Fatores no Modelo**

---

## 📊 **Comparando Modelos**

Qual o melhor modelo?

---

## 🏠 **4. Precificando as Casas**

---

### 📈 **Obtendo o R² da Previsão**

---

### 🏠 **Precificando uma Casa**

---

### 🏠 **Precificando Várias Casas**

---

## 🔍 **5. Investigando o Modelo**

### 🔄 **Multicolinearidade**

Quando duas ou mais variáveis que você está tentando estudar são tão parecidas que é difícil dizer o quanto cada uma delas está influenciando o resultado.

---

### 📊 **Análise dos Resíduos**

**Resíduos:** A discrepância entre os valores reais e os valores que o modelo prevê para os mesmos pontos de dados.

---
