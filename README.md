# ml_house_rent

# Construindo um Modelo de Regressão para Marketing

### **Objetivo**
Este desafio visa construir um modelo de regressão para entender a relação entre os investimentos em marketing (Youtube, Facebook, Newspaper) e o retorno de vendas. O modelo deve ser capaz de prever os retornos baseados nos investimentos realizados em cada plataforma.

## **Contexto**

Uma empresa investe mensalmente em publicidade online em plataformas como Youtube, Facebook e jornais. Os registros contêm dados dos investimentos e o retorno de vendas. A empresa deseja entender a relação entre esses dados e criar um modelo preditivo para estimar os retornos futuros com base no investimento.

### **Dados**

O dataset contém as seguintes colunas:
| **Coluna** | **Descrição** |
| --- | --- |
| youtube | Investimento em Youtube |
| facebook | Investimento em Facebook |
| newspaper | Investimento em jornal |
| sales | Retorno das vendas |

---
**Ferramentas recomendadas:**
- `Pandas` para manipulação de dados.
- Bibliotecas de visualização (ex.: `Matplotlib`, `Seaborn`) para explorar distribuições e relações.
  
## **Etapas de Desenvolvimento**

### **Etapa 1: Análise Descritiva**

- Carregamento do dataset utilizando o **Pandas**.
- Verificação da distribuição e os tipos de dados.
- Identificação das inconsistências como dados ausentes, duplicados ou outliers.
- Realizaçõ uma análise estatística para obter uma visão geral dos dados.

### **Etapa 2: Análise Exploratória**

- Exploração das relações entre as variáveis.
- Utilização de visualizações para identificar padrões e correlações.
- Investigação de outliers ou desvios que podem afetar a modelagem.

### **Etapa 3: Modelagem de Regressão**

- Construção de  um modelo de **regressão simples** para prever o retorno das vendas com base nos investimentos.
- Utilização de bibliotecas como **scikit-learn** para criar e treinar o modelo.

### **Etapa 4: Predição**

- Aplicação de modelo de regressão treinado para prever o retorno de vendas com base nos investimentos em marketing.
- Apresentação das previsões geradas para ajudar na tomada de decisão.

### Lições Aprendidas

- **Avaliação de Algoritmos:** Testar diferentes algoritmos de Machine Learning e escolher o mais adequado como modelo inicial.
- **Impacto dos Hiperparâmetros:** Identificar e entender quais hiperparâmetros têm maior impacto no desempenho do modelo.
- **Otimização de Modelos:** Utilizar **Grid Search** para realizar uma otimização exaustiva e aprimorar os parâmetros do modelo.

Com esses ajustes, conseguimos construir um modelo mais robusto e preciso para estimar os preços dos imóveis, com base nas variáveis disponíveis.

Esse estudo de caso é um exemplo prático de como aplicar **Machine Learning** para resolver problemas de regressão, abrangendo desde a **análise exploratória** até a **implantação do modelo** em produção.

## Recursos Complementares
- [**Python Graph Gallery**](https://www.python-graph-gallery.com/): Aprenda a criar visualizações eficazes.
- [**Scikit-Learn**](https://scikit-learn.org/stable/modules/clustering.html#clustering): Documentação de modelos de regressão e clustering.
