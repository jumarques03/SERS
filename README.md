# CP02 

Este repositório contém as resoluções dos exercícios **CP02-001** e **CP02-002**.

---

## 📂 Estrutura do Projeto

- `CP02_001_SERS.ipynb` → Exercícios **01** e **02** da parte **CP02-001**  
- `CP02_002_SERS.ipynb` → Exercícios **01** e **02** da parte **CP02-002**  
- `orange_fluxo.svg`, `Orange.ows` e `resultados_orange.zip` → Fluxo do Orange e resultados referente às análises 

---

## 📑 Exercícios e Datasets Utilizados

### 🔹 CP02-001

#### **Exercício 01 – Appliances Energy Prediction**  
- **Dataset:** [Appliances Energy Prediction (UCI)](https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction)  
- **Descrição:**  Este conjunto de dados contém informações ambientais de uma residência, como temperatura, umidade, pressão e hora do dia. A variável-alvo é o consumo de energia dos eletrodomésticos, medida em Wh (watt-hora). As colunas incluem date, Appliances, lights, e várias medições de temperatura e umidade interna e externa (T1, RH_1, T_out, RH_out, etc.).
- **Tamanho:** ~29.000 instâncias, 29 atributos.
- **Resultado Esperado:** Predição do consumo de energia de eletrodomésticos.

#### **Exercício 02 – Smart Grid Stability**  
- **Dataset:** [Smart Grid Stability (Kaggle)](https://www.kaggle.com/datasets/pcbreviglieri/smart-grid-stability)  
- **Descrição:** O dataset é uma simulação de uma rede elétrica inteligente. Ele inclui variáveis como potência ativa e reativa (p1, p2, p3, p4), e constantes de tempo (tau1, tau2, tau3, tau4). A variável-alvo, stabf, indica se a rede está stable (estável) ou unstable (instável).
- **Tamanho:** ~60.000 instâncias, 12 atributos.
- **Resultado Esperado:** Avaliação da estabilidade de redes inteligentes.

---

### 🔹 CP02-002

#### **Exercício 01 – Solar Energy**  
- **Dataset:** [Solar Energy Production (Kaggle)](https://www.kaggle.com/datasets/dronio/SolarEnergy)  
- **Descrição:** Contém dados para prever a radiação solar. As colunas incluem UNIXTime, Radiation, Temperature, Pressure, Humidity, WindDirection(Degrees), e Speed. A variável-alvo para a classificação (Nível de Radiação) foi criada com base na coluna Radiation, utilizando a mediana como limiar para definir os períodos de "Alta" e "Baixa" radiação.
- **Tamanho:** ~52.000 instâncias
- **Resultado Esperado:** Previsão da geração de energia solar.

#### **Exercício 02 – Wind Turbine SCADA Dataset**  
- **Dataset:** [Wind Turbine SCADA (Kaggle)](https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset)  
- **Descrição:** Este dataset inclui dados de operação de uma turbina eólica, como velocidade e direção do vento, além de informações de data e hora. O objetivo é prever a potência gerada, que é a variável-alvo LV ActivePower (kW). Outras colunas relevantes são Theoretical_Power_Curve (KWh) e Wind Direction (°).
- **Tamanho:** ~65.000 instâncias, 12 atributos.
- **Resultado Esperado:** Modelagem da produção de energia eólica.
