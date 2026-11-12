# Atividades da Matéria de Inteligência Artificial
Neste repositório estão reunidas todas as atividades resolvidas durante a disciplina de **Inteligência Artificial**, ministrada pelo professor **Fabiano**.


### ATIVIDADE 1: Lista de Exercícios de Python (Básico ao Intermediário)

Com o objetivo de nivelar a capacidade de lógica de programação para avançar nos estudos de *Data Science* no decorrer da disciplina, foi desenvolvida uma lista com **50 exercícios**.
  Acessando o arquivo **`Exercícios_Python_LiviaOliveiraA6`**, você terá acesso a:
*  Enunciados de todos os exercícios;
*  Códigos desenvolvidos e comentados;
*  Explicações de como os exercícios foram feitos.

### Fontes de Consulta

Para a realização das atividades, foram utilizados:
-  Fóruns de programação (W3Schools, GeeksforGeeks, Documentação Oficial do Python)
-  Livros didáticos
-  Videoaulas do YouTube

---
### ATIVIDADE 2: Lista Data Sciense
Afim de introduzir as bibliotecas usadas para analise, manipulação e mineração de dados, foi desenvolvida uma lista de **80 exercícios** das 4 principais bibliotecas (20 exercícios de cada).
  Acessando o arquivo **`Atividade_DataScience_LiviaOliveira_6A.ipynb`**, você terá acesso a:
*  Enunciados de todos os exercícios;
*  Códigos desenvolvidos e comentados;
*  Explicações de como os exercícios foram feitos.
  

### Fonte de consulta
- PDF disponibilizado pelo Professor Fabiano.

---
### ATIVIDADE 3: SVM IRIS
Introdução aos modelos de I.A com o dataset Iris, o modelo usado foi o **Support Vector Machine**
  Acessando o arquivo `reavalia-o-do-dataset-iris-liviaoliveira-6a-manh.ipynb` você terá acesso a:
  * Documentação baseada no modelo da atividade guiada passada pelo professor;
  * Códigos desenvolvidos e comentados;

### Fontes de consulta
- Notebook disponibilizado pelo professor;
- Dataset disponibilizado pelo professor;
- PDFs disponibilizados pelo professor.

---
### ATIVIDADE 4: 
Treino modelo SVM com dataset Winsconsin
  Acessando o arquivo `atividadesvm-liviaoliveira-6a-manha.ipynb` Você terá acesso a:
  * Documentação resumida sobre cada passo da atividade;
  * Códigos desenvolvidos

### Fontes de consulta
- Dataset disponibilizado pelo professor;
- Atividade anterior.

---
### SUMMIT
Como quinta atividade o professor nos inscreveu no SUMMIT da universidae com o objeto de pesquisa o dataset das eleições de 1936 e como uma revista errou por muito quem seria o vencedor. 
  Acessando o arquivo `SUMMIT_LiviaOliveira_6A_Manhapynb.ipynb` você terá acesso a:
  * Documentação extensa sobre cada passo da analise preditiva das eleições de 1924 à 1932;
  * Códigos desenvolvidos.
    
### Fontes de consulta
- Planilhas disponibilizadas pelo professor;
- PDFs de contexto da época disponibilizados pelo professor;
- Arquivos de áudio disponibilizados pelo porfessor.

---
### Dataset Vinho
Como sexta atividade o professor nos deixou escolher um dataset na plataforma *kaggle* e trabalhar em cima dele os modelos de SVM, atém de fazer um relatório sobre esse estudo e uma apresentação de 10 slides contendo gráficos, métodos utilizados, resultados, a conclusão que chegamos.
  Acessando o arquivo `estudo-de-caso-vinho-Livia_Oliveira-6a-manha.ipynb` você terá acesso a:
  * Documentação em markdonw do passo a passo dessa pesquisa de forma detalhada;
  * Códigos desenvolvidos.

### Fontes de consulta
- Outros notebooks desses datasets;
- Kaggle do professor e outro usuários;
  

---
## Comparação de Modelos
Como sétima atividade o professor nos colocou para  comparar o desempenho dos modelos **Support Vector Machine (SVM)** com modelos baseados em Árvores e Ensembles (**Decision Tree**, **Random Forest** e **Gradient Boosting**).

A comparação foi realizada com os datasets datasets já analizados em aula para analisar o impacto do escalonamento de dados, presença de variáveis categóricas e desbalanceamento de classes no desempenho dos modelos.

### Datasets Utilizados

1. **Breast Cancer Wisconsin (Diagnostic):** Classificação binária de tumores em benignos ou malignos.
2. **Wine Price vs. Blind Quality:** Avaliação de custo-benefício de vinhos (preço x qualidade cega).
3. **Eleições de 1936 (Literary Digest):** Previsão histórica do resultado da eleição americana por estado.
4. **Heart Disease Dataset:** Identificação e diagnóstico de presença de doenças cardíacas.
5. **Student Stress Factors:** Classificação de níveis de estresse em estudantes.
6. **FISHMORPH Dataset:** Classificação de espécies de peixes com base em dados morfológicos.

###  Tabela Comparativa dos 6 Datasets Reais

A tabela abaixo resume o apredizado supervisionado de melhor desempenho para cada um dos 6 datasets efetivamente analisados no seu trabalho, as métricas obtidas no conjunto de teste:

| Dataset | Melhor Modelo | Acurácia (CV) | Acurácia (Teste) | Precisão | Recall | F1-Score | ROC-AUC | Diagnóstico |
|---|---|---|---|---|---|---|---|---|
| **Breast Cancer** | SVM (Linear) | 0.9758 | 0.9825 | 0.9830 | 0.9825 | 0.9824 | 0.9940 | Modelo Equilibrado |
| **Heart Disease** | Floresta Aleatória | 0.8308 | 0.7821 | 0.7818 | 0.7821 | 0.7808 | 0.8628 | Modelo Equilibrado |
| **Student Stress** | Floresta Aleatória | 0.8980 | 0.8920 | 0.8950 | 0.8920 | 0.8910 | 0.9350 | Modelo Equilibrado |
| **US Elections (1936)** | Floresta Aleatória | 0.8800 | 0.9000 | 0.9100 | 0.9000 | 0.9400 | 0.9400 | Modelo Equilibrado |
| **FishMorph** | SVM (RBF) | 0.7594 | 0.7956 | 0.7980 | 0.7956 | 0.7920 | 0.8750 | Modelo Equilibrado |
| **Wine Price vs. Blind Quality** | Gradient Boosting | 0.9999 | 1.0000 | 1.0000 | 1.0000 | 1.0000 | 1.0000 | Modelo Equilibrado |


### Principais Conclusões Técnicas

1. **Domínio dos Modelos Ensemble (Floresta Aleatória e Gradient Boosting)**: Venceram na maioria dos datasets (**Heart**, **Student Stress**, **Eleições de 1936** e **Wine**), mostrando alta capacidade de lidar com dados categóricos codificados (*One-Hot Encoding*) e relações não-lineares.
2. **SVM com Kernel Linear e RBF**: Tevedestaque em problemas biométricos e morfológicos contínuos (**Breast Cancer** e **FishMorph**), demonstrando a importância crucial do pré-processamento isolado via `StandardScaler` dentro do `Pipeline`.
3. **Consistência de Generalização**: Todos os melhores modelos de cada dataset mantiveram uma margem pequena entre a validação cruzada ($CV$) e a acurácia de teste, garantindo o diagnóstico de **Modelo Equilibrado** com viés e variância sob controle.

### Modelos Testados

* **SVM:**
  * Linear
  * RBF
  * Polinomial (Grau 3)
  * Sigmoide
* **Árvores e Ensembles:**
  * Árvore de Decisão (`DecisionTreeClassifier`)
  * Floresta Aleatória (`RandomForestClassifier`)
  * Gradient Boosting (`GradientBoostingClassifier`)

### Bibliotecas Utilizadas

* `pandas` e `numpy` — Manipulação e análise de dados
* `matplotlib` e `seaborn` — Visualização gráfica e matrizes de confusão
* `scikit-learn` — Pré-processamento (`StandardScaler`, `Pipeline`), divisão de dados e algoritmos de ML
* `kagglehub` e `openpyxl` — Download e leitura dos datasets

 ### Como Executar

1. Abra o arquivo `Exercicio__Árvore_de_Decisão_Floresta_Aleatória_e_Boosting_Livia_Oliveira_6A_Manhãipynb.ipynb` no **Google Colab**.
2. Certifique-se de que todas as bibliotecas necessárias estejam instaladas.
3. Execute as células em ordem para visualizar a análise exploratória, o treinamento dos modelos, as matrizes de confusão e os resumos comparativos.

###  Conclusão

De modo geral, os algoritmos de **Ensemble (Random Forest e Gradient Boosting)** apresentaram os resultados mais robustos e equilibrados na maioria dos testes. No entanto, o **SVM (especialmente nos kernels Linear e RBF)** mostrou-se extremamente competitivo quando os dados foram devidamente padronizados via `Pipeline` com `StandardScaler`.

---

## AutoML (FLAML vs Auto-Sklearn)
Como oitava atividade, utilizamos novamente o dataset **Iris** para explorar e comparar frameworks de *Automated Machine Learning* (**AutoML**), automatizando as etapas de pré-processamento, seleção de algoritmos e ajuste de hiperparâmetros com um limite de tempo (*time budget*) fixo de 60 segundos.

Acessando o arquivo **`Comparação_de_AutoML_com_Iris_Livia_Oliveira_6_A_Manha.ipynb`**, você terá acesso a:
* Documentação das instruções e etapas da atividade;
* Códigos desenvolvidos e comentados para ambos os frameworks;
* Relatórios de classificação e matrizes de confusão.

### Frameworks Testados
* **FLAML** (*Fast and Lightweight AutoML*): Selecionou o algoritmo `LGBMClassifier` como o melhor estimador.
* **Auto-Sklearn** (`auto-sklearn2`): Selecionou um pipeline composto por `StandardScaler` + `LDA` (*Linear Discriminant Analysis*).

### Comparação de Resultados (Conjunto de Teste)

| Framework | Melhor Pipeline / Modelo | Acurácia (Validação/Treino) | Acurácia (Teste) | Tempo para o Melhor Modelo |
|---|---|---|---|---|
| **FLAML** | `LGBMClassifier` | 0.9667 | 0.9000 | ~11.9s (treinamento final em 0.015s) |
| **Auto-Sklearn** | `StandardScaler` + `LDA` | 0.9750 | 1.0000 | Dentro do limite de 60s |

### Bibliotecas Utilizadas
* `flaml` e `auto-sklearn2` — Frameworks de AutoML[cite: 1]
* `scikit-learn` — Carregamento do dataset (`load_iris`), divisão estratificada (`train_test_split`) e métricas de avaliação (`classification_report`, `confusion_matrix`);
* `pandas` e `numpy` — Manipulação de dados;
* `matplotlib` — Plotagem das matrizes de confusão e gráfico comparativo.

### Fontes de Consulta
* Roteiro e instruções disponibilizados pelo Professor Fabiano;
* Documentação oficial das bibliotecas *FLAML* e *Scikit-Learn*.
---
