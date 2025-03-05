# Clusterizacao
📊 Clusterização na prática: agrupando clientes por consumo de energia com Machine Learning! ⚡

A clusterização é uma técnica essencial de Machine Learning que nos permite segmentar dados em grupos com características semelhantes. Hoje, vou mostrar como utilizamos essa abordagem para analisar padrões de consumo de energia elétrica.

🔍 O que fizemos?
Trabalhamos com um conjunto de dados real da França, disponibilizado pelo UCI, contendo mais de 2 milhões de registros de consumo elétrico. Nosso objetivo foi agrupar consumidores por similaridade, ajudando a entender perfis distintos de consumo.

🛠 Passo a passo:
✅ Pré-processamento dos dados: Ajustamos os tipos de variáveis e removemos valores ausentes.
✅ Amostragem: Reduzimos os dados para evitar sobrecarga de memória.
✅ Redução de dimensionalidade: Aplicamos PCA (Principal Component Analysis) para transformar 7 variáveis em apenas 2 principais, mantendo a essência da informação.
✅ Clusterização com K-Means: Utilizamos diferentes valores de K para encontrar a melhor segmentação dos clientes.
✅ Métrica de avaliação: Aplicamos o silhouette score e analisamos a soma dos quadrados intra e inter-clusters para validar a qualidade dos agrupamentos.

📌 Por que isso é importante?
Esse tipo de análise pode ser usado em diversas áreas:
🔹 Marketing: para personalizar campanhas de acordo com o perfil dos clientes.
🔹 Vendas: para identificar consumidores com potencial de aumento no consumo.
🔹 Crédito & Cobrança: para prever perfis de inadimplência e ajustar políticas de crédito.

🧠 Insights interessantes:
➡️ Alguns consumidores possuem padrões de consumo bastante distintos, exigindo estratégias específicas de tarifação.
➡️ A redução de dimensionalidade facilitou a segmentação e permitiu melhor visualização dos clusters.
➡️ O método K-Means provou ser eficiente para identificar grupos bem definidos.
