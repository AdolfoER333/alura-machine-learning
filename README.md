# Formação Machine Learning

Visível em https://www.alura.com.br/formacao-machine-learning e agrupada pela Alura. Abaixo, uma descrição breve dos conteúdos abordados em cada curso já na ordem da formação.

## (1) Machine Learning: Introdução à classificação com SKLearn

• Uso de algumas funções de classificação (LinearSVC e SVC) do módulo scikit.svm, que implementa o método máquinas de vetores de suporte para as primeiras previsões;<br/>
• Funções para mensurar acurácia, separar dados entre treino e teste além de padronização com StandardScaler;<br/>
• Visualização do conjunto de dados para o caso em que dim(X)=2;<br/>
• Apresentação da árvore de decisão com DecisionTreeClassifier, caso em que os critérios precisos de decisão do algoritmo são visíveis.

## (2) Machine Learning: Classificação por trás dos panos

• Uso do MultinomialNB e AdaBoostClassifier para classificação e uma intuição sobre como o Naive Bayes funciona;<br/>
• Transformação de variável categórica em algumas variáveis binárias;<br/>
• Importância de separar uma parte do conjunto de dados para validação: nunca usar uma mesma partição para tomar duas decisões diferentes (treinar e testar; ou testar e validar);<br/>
• A performance experada real do algoritmo é aquela atingida no conjunto de validação.

## (3) Machine Learning: Lidando com dados de muitas dimensões

• Formas de diminuir as dimensões: limpar dimensões nulas ou constantes, análise de dimensões correlatas e formas automatizadas do sklearn (KBest, RFE, RFECV);<br/>
• Visualizações violinplot e heatmap do seaborn, usando dados das matrizes de correlação e confusão;<br/>
• Redução de dimensionalidade com RFE, PCA e TSNE, sendo os dois últimos específicos para isso, e visualização dos dados em duas dimensões;<br/>
• Utilização do RandomForestClassifier para todas as classificações do curso.

## (4) Clustering básico: k-means, DBSCAN e mean shift

• Prática com agrupadores KMeans, DBSCAN e MeanShift, do módulo scikit.cluster;<br/>
• Visualizações em duas dimensões (incluindo com redução de dimensionalidade) dos clusters formados com a biblioteca plotly;<br/>
• Cálculo do coeficiente de silhueta médio como métrica de comparação entre os algoritmos;<br/>
• Contato inicial com dados não rotulados.

## (5) Clustering: extraindo padrões de dados

• Métricas para validação de clusters: coeficiente de silhueta e índices davies-bouldin e calinski-harabasz, além da base matemática por trás deles;<br/>
• Diferença entre dados rotulados e não-rotulados e dificuldades associadas à falta de rótulos;<br/>
• Comparações entre métricas para classificação dos clusters;<br/>
• Seleção de variáveis mais influentes na formação dos clusters e análise dos agrupamentos com base nos valores selecionados.

## (6) Machine Learning: Validação de modelos

• Ideia mais próxima da real quanto à performance esperada de um modelo, incluindo o intervalo de confiança;<br/>
• O que é validação cruzada e quais as vantagens em relação ao holdout e implementação por meio do cross_validation;<br/>
• KFold, StratifiedKFold e GroupKFold como formas de embaralhar ou garantir a organização do conjunto de dados para a validação cruzada;<br/>
• Necessidade da pipeline pela execução de processos sequenciados.

## (7) Machine Learning parte 1: otimização de modelos através de hiperparâmetros

• O que são hiperparâmetros e como mudam o modelo, no caso, exemplificado com o DecisionTreeClassifier;<br/>
• Observação clara e intuitiva de como ocorre o overfitting usando o parâmetro de profundidade máxima da árvore de decisão;<br/>
• GridSearchCV para otimização dos hiperparâmetros definidos dentro de um modelo;<br/>
• A necessidade da técnica de nested cross validation quando trata-se da escolha de um modelo (avaliação de performance) aliada ao refino de hiperparâmetros.
