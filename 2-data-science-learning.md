<h4><a href="blank_">[En]</a> | <a href="blank_">[Pt-Br]</a></h4>
<h4>
    <p>Objetivo : Explicar sobre conhecimentos adquiridos para se tornar um Data Scientist com python<br>
    Público alvo : A partir do momento que se entende por gente
    </p>
</h4>

<h1 align="center">DATA SCIENTIST - LEARNING</h1>
Iniciei os estudos em Data Science em 01/05/2020 e a seguir descrevo uma parte do conhecimento de qualidade que adquiri/obtive :
</p>

<h3>OVERVIEW</h3>
<ol>
    <li>O que é, para que serve e como usar Data Science</li>
    <li>A diferença entre Data Science e áreas correlacionadas como Big Data, Data Analysis, Business Analysis, Data Engineer, entre outros</li>
    <li>A diferença entre Machine Learning, Deep Learning, Neural Networks na Inteligência Artificial</li>
    <li>Como utilizar a ferramenta microsoft visual studio code no desenvolvimento de soluções Data Science utilizando a linguagem de programação python</li>
    <li>Como utilizar as ferramentas jupyter notebook e google labs no desenvolvimento de soluções Data Science utilizando a linguagem de programação python</li>
    <li>A importância do <a href="https://github.com/claudineien/graduate-datascientist/blob/master/00lifecycledatascience.md">ciclo de vida de uma solução em Ciência de Dados</a></li>
    <li>Algumas otimizações em python específicas à Data Science</li>
    <li>Todas as principais bibliotecas utilizadas em machine learning e deep learning com uso em machine learning</li>
    <li>A importância da qualidade do dataset para o modelo machine learning e/ou deep learning</li>
    <li>A importância da qualidade da limpeza e preparação do dataset para o modelo machine learning e/ou deep learning</li>
    <li>Todas as principais técnicas utilizadas em machine learning e deep learning com uso em machine learning</li>
    <li>A importância da boa comunicação com os stakeholders envolvidos projeto Data Science</li>
    <li>A importância em documentar desde a definição do problema ao deploy em produção em projetos Data Science</li>
</ol>

<h3>BIBLIOTECAS, OBJETOS E MÉTODOS EM PYTHON</h3>
<p>Comuns em qualquer projeto Data Science
    <ul>
        <li>pandas</li>
        <li>pandas-profiling</li>
        <li>xlrd</li>
        <li>openpyxl</li>
        <li>cufflinks</li>
        <li>chart_studio</li>
        <li>scikit-learn</li>
        <li>sklearn</li>
        <li>numpy</li>
        <li>ipywidgets</li>
        <li>pydot</li>
        <li>graphviz</li>
        <li>seaborn</li>
        <li>matplotlib</li>
        <li>plotly</li>
        <li>plot</li>
        <li>scipy</li>
        <li>mlxtend</li>
    </ul>
</p>

<p>Text mining
    <ul>
        <li>fuzzywuzzy</li>
        <li>levenshtein</li>
        <li>nltk | nltk.download()</li>
        <li>statsmodels</li>
        <li>textblob</li>
    </ul>
</p>

<p>Tratamento de imagens e reconhecimento facial em fotos e/ou pela webcam
    <ul>
        <li>keras</li>
        <li>pillow</li>
        <li>cv2</li>
        <li>mtcnn</li>
        <li>tensorflow</li>
        <li>opencv</li>
    </ul>
</p>

<p>Scraper de páginas html, xml
    <ul>
        <li>BeautifulSoup</li>
        <li>requests</li>
        <li>youtube_dl</li>
        <li>Scrapy</li>
    </ul>
</p>

<p>Classificadores
    <ul>
        <li>sklearn.neighbors - KNeighborsClassifier</li>
        <li>sklearn.naive_bayes - MultinomialNB</li>
        <li>sklearn.tree - DecisionTreeClassifier</li>
        <li>sklearn.ensemble - RandomForestClassifier</li>
        <li>sklearn.linear_model - LogisticRegression</li>
        <li>lightgbm - LGBMClassifier</li>
    </ul>
</p>

<p>Transformar palavras
    <ul>
        <li>sklearn.feature_extraction.text - TfidfVectorizer</li>
        <li>scipy.sparse hstack</li>
        <li>scipy.sparse vstack</li>
    </ul>
</p>

<p>Métricas para analisar e validar resultados
    <ul>
        <li>metrics.classification_report</li>
        <li>pandas - crosstab</li>
        <li>sklearn.model_selection - cross_val_predict</li>
        <li>predict_proba</li>
        <li>sklearn.metrics - roc_auc_score</li>
        <li>sklearn.metrics average_precision_score</li>
    </ul>
</p>

<p>Estatística Descritiva
    <ul>
        <li>scipy.stats.mstats - gmean, hmean</li>
    </ul>
</p>

<p>Bayesian Optimization
    <ul>
        <li>skopt - forest_minimize</li>
    </ul>
</p>

<p>Pipeline
    <ul>
        <li>sklearn.pipeline - make_pipeline</li>
    </ul>
</p>

<p>Criar estrutura para demonstrar a solução Data Science
    <ul>
        <li>app com Flask</li>
        <li>app com streamlit</li>
        <li>container com Docker</li>
        <li>deploy no Heroku</li>
    </ul>
</p>

<p>Bibliotecas para trabalhor Banco de dados
    <ul>
        <li>SQLAlchemy</li>
        <li>pymysql</li>
        <li>mysql-connector-python</li>
        <li>sqlite3</li>
    </ul>
</p>

<p>SQL Data Base
    <ul>
        <li>My Sql</li>
        <li>SQLite3</li>
    </ul>
</p>

<h3>DIVERSAS TÉCNICAS IMPORTANTES</h3>
<p>
    <ul>
        <li>De amostragem</li>
        <li>Upsampling</li>
        <li>Downsampling</li>
        <li>Problem Framing</li>
        <li>Feature Engineering</li>
        <li>Engenharia de Features para Séries temporais: Sazonalidade, Janelas de tempo (lag)., Janelas de tempo com estatísticas</li>
        <li>Automatizar modelos com pipelines</li>
    </ul>
</p>

<h3>APLICAÇÃO DO CONHECIMENTO EM QUALQUER PROJETO REAL</h3>
<p>
Tão importante quanto todos as bibliotecas, métodos, objetos em python, banco de dados sql ou nosql é a metodologia para aplicar a solução direcionada do cliente.</p>
<p>Atualmente aplico em meus projetos de aprendizado a técnica do <a href="https://github.com/claudineien/graduate-datascientist/blob/master/00lifecycledatascience.md">ciclo de vida de uma solução em ciência de dados</a> cumprindo os seguintes passos :
    <ol>
        <li>definir o problema</li>
        <li>definir a melhor solução</li>
        <li>definir a melhor solução em machine learning e/ou deep learning e/ou neural networks</li>
        <li>definir como a solução será usada produtivamente</li>
        <li>definir como testar a solução desenvolvida</li>
    </ol>
</p>
<p>Esta técnica cobre todo o aspecto de ouvir o cliente, entender o que o cliente precisa mesmo que esteja com dificuldade de transmitir o que precisa, orientar o cliente na definição do problema e da melhor solução, ter uma forte presença no projeto, ter uma forte e clara comunicação com todos os envolvidos no projeto, desenvolver o melhor trabalho possível no dataset para que o modelo machine learning, deep learning e/ou neural networks tenha a eficiência, eficácia e efetividade esperada, desenvolver pequenos projetos testes para identificar a solução mais adequada em machine learning, deep learning e/ou neural networks para resolver o problema, conseguir escolher o melhor modelo ao aplicar as técnicas de métricas e validações dos modelos, documentar cada passo realizado juntamente com a equipe envolvida, aplicar o ETL-Extract Transform Load com alta qualidade e documentar o que for necessário para evitar dúvidas sobre o projeto data science.
</p>

<h3>CONHECIMENTOS COMPLEMENTARES</h3>
<p>Até o momento não apliquei Data Science sob estas tecnologias. Estão na mira.</p>
<p>
    <ul>
        <li>ERP Protheus Totvs S.A</li>
        <li>AWS Amazon</li>
        <li>OutSystems Platform</li>
    </ul>
</p>

<!--Boas práticas para analisar os dados
Boas práticas para gerar dados para teste
Boas práticas para salvar os projetos
Testar modelos simples sobre os datasets, para decidir o modelo mais adequado a solução

Realizar coleta de dataset com 
Analisar, Interpretar de time series com identificação de padrões machine learning
Identificar soluções para problemas de previsão
estatística
Conhecimento em SQL
Conhecimento em AWS
Conocimientos o experiencia en NLP
Aprendi a utilizar a criatividade para melhorar limpar os dados Aprendi a utilizar a criatividade para melhora o modelo machine learning
X A I - Explainable AI - Inteligência Artificial compreensivel aos humanos
improve efficiency by delivering data science systems
Several Graphs Plots 
providing statistical support to enable data-driven business decisions
create predictive models
statistical matters
create high quality statistical models
mining complex data
técnicas para discover the information hidden in vast amounts of data and to make smarter decisions
analytical mindset to dig into and gather relevant data, research, train, and test models and modeling techniques suitable, you will support
aprenti sobre a delivering results back to the business in a tangible and coherent way
Processing, cleansing, and verifying the integrity of data used for analysis
predictive using machine learning techniques
Aprendi técnicas para Identify improvements to current processes and investigate future opportunities to the various functions in the organization
Support strategic efforts to engage the wider organization in this space
Manage testing cycles
Doing ad-hoc analysis as required and presenting results in a clear manner we also expect from you:
Pursuing a Master’s (preferred) or Bachelor's Degree (required) in Business Analytics, Mathematics, Statistics, Computer Science, or equivalent degree with a data science focus
Aprendi a trabalhar com Hadoop, Spark
Interesse/conhecimentos em Machine learning e Deep learning
Aprendi a utilizar os algorítmos keras
Nível iniciante com TensorFlow
Construir modelos que apoiam e aumentam o conhecimento sobre o setor em trabalho
Automação de reporting nas vertentes funcional e técnica (ETL, analítica e reporting)
Conhecimento iniciante em quantitative systems and forecasting models that generate predictions of the highest level of visibility and importance for MegaBeetle financial and operational planning
will partner with software developers and data engineers to build end-to-end data pipelines and production code, and you will have exposure to senior leadership as we communicate results and provide scientific guidance to the business
Improve upon existing methodologies by developing new data sources, testing model enhancements, and fine-tuning model parameters
Experiência com SQL e bases de dados relacionais
Capacidade crítica e sentido de detalhe
Utilizando pragmatism para desenvolver 
Knowledge of probability and statistical models (e.g, Distributions, Statistical Inference, Hypothesis testing, Bayesian framework, etc)
transformarem dados em vantagem competitive
desenvolvemos e implementamos soluções, que garantem Receitas, Custos e Margens, Gestão de Risco e Fraude, e Eficiência Operacional
Probability and statistics, exploratory data analysis, linear regression, hypothesis testing.
Develop highly reliable and scalable systems that go into real products
statistical and machine learning models such as regressions, Markov, decision trees, clustering, neural networks, convolutional networks, deep learning, graphs, LDA, SVM
time series analysis
Mallet, Tensor Flow, SageMaker
Experience with Big Data ML toolkits, such as Mahout, SparkML or H20, Hadoop, Spark, Flink, Kafka
Skills in quantitative analysis, problem definition, synthesis & recommendation development will be essential
Set up a test (A/B test or pre-post) to measure performance in the best possible way
Prior experience in performance measurement, creatively applying regression techniques/modelling, optimization techniques, A/B testing, etc for business applications
Deep understanding of statistics, experimental design, and causal inference
Aprendizado em Able to spot and pursue opportunities as well as to translate high-level directions into practical projects and lead/drive their completion with minimal supervision.
Executes at all stages of model development and delivery including data definition, sampling, preprocessing, feature selection, model generation, and validation and support of production model release with an emphasis toward the latter stages of model development.
Ability to leverage Cloud computing services
Skilled in visualization (Tableau or Power BI)
Experience in working with numpy, scipy, scikit-learn, pandas
Experience reporting machine learning accuracy and precision in industry
You are familiar with (in no particular order): logistic regression, gradient descent, regularization, cross-validation, overfitting, bias, variance, convex optimization, eigenvectors, relational databases, SQL, latency, computational complexity, sparse matrices, feature engineering, clustering
data scientists draw on quantitative methods and business intuition to uncover learnings that drive key business decisions
to develop data pipelines, identify areas of interest and provide solutions
Sólida experiência em estatística descritiva, com capacidade de exploração de dados utilizando Python e base Hive,
Conhecimento de Tensorflow, Keras e Torch
Experiência em manipulação de dados (data cleaning, data augmenting, data selection)
Definir e implementar análises exploratórias de dados
Mineração de texto (Caracterização, sumarização, agregação)
Jupyter/RStudio; SQL e Oracle; NoSQL e MongoDB;
Full-text search e ElasticSearch;
Plataforma AWS (S3, EC2, EMR, Athena, DynamoDB);
Inferência estatística uni/multivariada, regressões e séries temporais;
Aprendizado de máquina (Árvores de decisão e Redes Neurais);
Deep learning (CNN, RNN, LSTM) aplicada a processamento de texto e imagens;
Restful APIs e swagger;
Versionamento de código em Git;
MapReduce, Hadoop, Spark
Como trabalhamos com dados de varejo físico, irá trabalhar com dados real-time e batch de mais de 40 milhões de Preços e Sortimento por dia(entre dados internos e externos), focamos em criar Produtos de Dados que auxiliem ou criar produto final, produtos leitura de vídeo, classificação automática de produtos, previsão de promoção, normalização de preço de produtos por atacado e varejo, recomendação de produtos de uma mesma sortimento dos varejistas, extração de features de produtos, validação de sortimento e ruptura permanente de produtos
Acompanhar dados e métricas da Mobile Intelligence (ASO/SEO) e Reviews Intelligence (monitoramento de App Stores), bem como a utilização desses dados para a criação de modelos preditivos e a elaboração de dashboards para clientes, dando suporte ao time de estratégia e atendimento
Criação de Dashboards com indicadores focados em resolução de problema específicos da área da saúde (por exemplo, tempo de tratamento em oncologia, linhas de tratamento em doenças inflamatórias, etc)


</p>

GIT HUB
GIT


Todos os dias procuro por
. conhecer sobre melhores práticas, conceitos e tecnologias relacionadas a segurança na web, redes internas, apps, mobiles, emails, com python, com javascript, com data science e como aplicá-las
. conhecer tecnologias cloud como aws amazon (maior interesse), azure e google cloud
. aprender novas técnicas e tecnologias e como aplicar no mundo real
. aplicar novas técnicas que aprendi
Gosto de conversar com pessoas sem conhecimento algum com tecnologia, do ponto de vista técnico, para aprender sobre que seria bom às pessoas
Gosto de conversar com pessoas consideradas usuários avançados no uso de tecnologias, para aprender como e aonde melhorar as ferramentas tecnológicas, apps, tecnologias existentes e/ou até criar com a nova funcionalidade
Gosto de conversar com profissionais iniciantes, por que a dúvida destes me ajudam a me focar em soluções que ainda não pensei
Gosto de conversar com profissionais experientes, para aprender sobre as melhores práticas, evitar erros já conhecidos, saber quais são problemas ainda não resolvidos (issues) , aplicar o que esta sendo utilizado por profissionais experientes


<h1 align='center'>PASSOS</h1>
<h3>ENTENDER O QUE CONCEITO </h3>
<p>Auxiliar o pesquisador a encontrar o melhor ponto de corte no score de determinados classificadores machine learning sob determinados grupos que estão sendo analisados.<br><br>
Importante que o dataset seja o mesmo utilizado em todos os classificadores machine learning.<br><br>
Perguntas que a curva ROC deve responder :<br>
<ol>
    <li>A partir de qual score no classificador machine learning é possível classificar corretamente o alvo desejado ?</li>
    <li>Qual a proporção de alvos corretamente classificados ?</li>
</ol>
<p>
Também auxilia a explicar a escolha de determinado classificador machine learning do ponto de vista científico-técnico.</p>
Dois termos a observar :<br>
<table>
    <thead>
    <tr>
        <th>Termo</th>
        <th scope="col">Definição</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td scope="row">Sensibilidade</td>
        <td>Probabilidade do alvo ser corretamente classificado. A classificação do classificador machine learning confirma a classificação real. Significa que o classificador é sensível para classificar o alvo desejado.</td>
    </tr>
    <tr>
        <td scope="row">Especificidade</td>
        <td>Probabilidade do não alvo ser corretamente não classificado. A classificação do classificador machine learning confirma a classificação real.</td>
    </tr>
    </tbody>
</table>
<p><strong>Importante :</strong> É raridade em uma mesma classificação, obter 100% de sensibilidade e 100% especificidade.
</p><br>
<p>Fontes de erro :<br>
Falso Positivo : Na classificação real o Alvo é falso, mas para o classificador machine learning o Alvo é verdadeiro.<br>
Falso Negativo : Na classificação real o Alvo é verdadeiro, mas para o classificador machine learning o Alvo é falso.
    <table>
        <thead>
        <tr>
            <td colspan="2"><td>
            <td colspan="0"><strong>Classificação Real</strong></td>
        </tr>
        <tr>
            <td colspan="2"></td>
            <th scope="col">Alvo</th>
            <th scope="col">Não-Alvo</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th>Classificação</th>
            <td scope="row">Alvo</td>
            <td><strong>Verdadeiro Positivo</strong></td>
            <td>Falso Positivo</td>
        </tr>
        <tr>
            <th>Machine Learning</th>
            <td scope="row">Não-Alvo</td>
            <td>Falso Negativo</td>
            <td><strong>Verdadeiro Negativo</strong></td>
        </tr>
        </tbody>
    </table>
</p>
<p>O <strong>modelo machine learning ideal</strong> será quando a proporção entre falso negativo e falso positivo for a menor possível e quando o acerto do verdadeiro positivo e verdadeiro negativo for a maior possível.</p>
<p>Importante saber que ao aumentar a sensibilidade perde-se na especificidade e vice-versa.</p>
<br>
<img src=".\notebook\dados_brutos\grafico_roc.png">
<br>
<p>
NÃO ALVO = Dados que não interessa<br>
ALVO = Dados que interessam<br>
ESCORE = É a escala de medida<br>

</p>
<hr>
<p><strong>roc_auc_score()</strong><br>
    todos os elementos positivos e as probabilidades de serem  positivos ou não<br>
    todos os elementos negativos e as probabilidades de serem negativos ou não<br>
    o score de um elemento probabilidade positivo é maior
    que o elemento probabilidade negativo = True<br>
    o score de um elemento probabilidade positivo é maior
    que o elemento probabilidade negativo = False<br>
    calcular a média dos resultados valores True e False<br>
<strong>Pergunta e resposta :</strong><br>
    Average precision:  média ponderada de cada precisão, usando como peso a precisão anterior.
    AUC: É a área sobre a curva ROC (TP x FN)
    Resposta : As duas são AUC (área sob a curva), o que muda é a curva. Uma é a curva de precision-recall (average_precision, AUPRC) e a outra é a curva ROC (roc_auc_score, ROC-AUC)
</p>

<p><strong>Aprender mais :</strong><br>
<a href="https://qastack.com.br/stats/51275/what-is-the-difference-in-what-aic-and-c-statistic-auc-actually-measure-for-mo">AIC e a c-estatística (AUC)</a><br>
<a href=""> A</a><br>
<a href=""> B</a><br> 
<a href=""> C</a><br>
<a href=""> D</a><br>
</p>
<br>
<hr>
<p>Fontes :
    <ul>
        <li><a href="https://curso.mariofilho.com/">   
        Curso Solução Completa de Data Science - Instrutor Mario Filho-Kagle Gran Master</a></li>
        <li><a href="https://www.youtube.com/watch?v=NbnVfpRJNp0">CURVA ROC</a></li>
    </ul>
</p>

<hr>
<h3> h3 </h3>
    <ul>
        <li> li </li>
    </ul>


<p><strong>Dica :</strong><br>
p
</p>

<p><strong>Nota :</strong><br>
p
</p>

<hr>
<h3> h3 </h3>
    <ul>
        <li> li </li>
    </ul>
<p> p 
</p>

<hr>
<h3> h3 </h3>
    <ul>
        <li> li </li>
    </ul>

<p><strong>Aprender mais :</strong><br>
<a href="​https://"> link</a><br>
</p>

<br>
<p><strong>Dica :</strong><br>
p
</p>

<p><strong>Nota :</strong><br>
p
</p>

<h3> h3 </h3>
<p> p 
    <ul>
        <li> ul li</li>
    </ul>
</p>
<h4> h4 </h4>
<p> p </p>

<h4> h4 </h4>
<p> p </p>
<p> p
    <ul>
        <li> li </li>
        <ul> ul
            <li> li </li>
        </ul>
    </ul>
</p>

<p> p 
    <ol> ol
        <li> li </li>
    </ol>
</p>

<h3> h3 </h3>
<p> p </p>

<h4> h4 </h4>
<p> p </p>
<p> p
    <ul> ul
        <li> li </li>
    </ul>
</p>
-->
<!--
<p>labelling</p>
<p>Active learning</p>
feather-format 0.4.1
pip install feather-format
https://pypi.org/project/feather-format/
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>
<p> - = - + + : > < { [ * & % $ # @ ! } ]</p>-->
