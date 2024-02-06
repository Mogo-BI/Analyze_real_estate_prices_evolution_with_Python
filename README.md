# Analyze real estate prices evolution with Python

<h1>I. Context</h1>

I did a consulting mission like a BI Analyst in **Les Plus Beaux Logis de Paris**, a prestigious B2B & B2C real estate company.

For financial reasons, this family firm wished to sell assets to ensure a sufficient level of cash flow.

The CEO's children were engaged in a real battle because none of them wanted to sell their assets (his son had the private market and his daughter had the corporate market). In fact I had a referee position in that situation.

CEO heard about datascience technics who could predict assets valorization. He asked me to did a study on parisian real estate prices evolution, by using machine learning algorithm, in order to determine which segment will be the most valuable in couple of years.**1st part of my mission**

Also, in order to falicitate their research works, his daughter wished I make available to them an algorithm which could predict and automatically classify their opportunities, depending on types of properties. **2nd part of my mission**

<h1>II. Methodology</h1>
  <h2>1. Preparing dataset for 1st part</h2>
    <li>Checking data types</li>
    <li>Dataset cleaning by removing not necessary data</li>
    <li>Using calculations to create new variables (like square meter prices)</li>

  <h2>2. Data analysis for values predictions</h2>
    <li>Carrying out correlation tests (Pearson/Spearman) to evaluate relationship between variables</li>
    <li>Analysis of prices evolution between private and corporate segments</li>
    <li>Using 'One hot encoding' to prepare data to be ready to train our machine learning algorithm</li>
    <li>Using 'train_test_split' to train and test our supervised algorithm</li>
    <li>Using a Linear regression to predict values of each segments</li>

  <h2>3. Preparing dataset for 2nd part</h2>  
    <li>Checking data types</li>
    <li>Dataset cleaning by removing not necessary data</li>
    <li>Using calculations to create new variables (like square meter prices)</li>
    
  <h2>4. Data analysis for automatic classification</h2>
    <li>Using a non-supervised algorithm, 'K-Means' to assign data around 2 centroïds (= prototypes data)</li>
    <li>Sample allocation in 2 clusters (around centroïds) which define types of properties (private or corporate)</li>

  <h2>5. Presentation of results</h2>
    <li>Presenting a report with visualizations and methodology applied as well as the results to their requests</li>

<h1>III. Technologies & skills</h1>

  <h2>1. Technologies</h2>

  <h2>2. Assessed kills</h2>
    <li>Convince the client of the results relevance by justifying the methodology followed</li>
    <li>Perform correlation analysis</li>
    <li>Perform a multivariate analysis</li>
    <li>Present a predictive analysis</li>
    <li>Carry out a linear regression in order to make estimates or predictions</li>

<h1>IV. References</h1>

  <h2>1. Data</h2>
    <li><a href="https://openclassrooms.com/fr/courses/6204541-initiez-vous-a-python-pour-lanalyse-de-donnees">Openclassrooms : Initiez vous à Python pour l'analyse de données</a></li>
    <li><a href="https://openclassrooms.com/fr/courses/8063076-initiez-vous-au-machine-learning">Openclassrooms : Initiez vous au machine learning</li>
    <li><a href="https://pandas.pydata.org/docs/reference/api/pandas.read_excel.html">Pandas : Fonction pandas.read_excel</li>
    <li><a href="https://runebook.dev/fr/docs/pandas/user_guide/indexing">Runebook.dev : Documentation indexation et sélection de données Pandas</li>
    <li><a href="https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html">Matplotlib : Documentation réalisation graphiques pyplot</li>
    <li><a href="https://www.jmp.com/fr_fr/statistics-knowledge-portal/what-is-correlation/correlation-coefficient.html">Jmp Statistic : Documentation coefficient corrélation</li>
    <li><a href="https://www.youtube.com/watch?v=iUVBpTeemjU&t=381s">Youtube 'CNRS' : One hot encoding & embedding</li>
    <li><a href="https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html">Sickitlearn : train_test_split</li>
    <li><a href="https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html">Sickitlearn : LinearRegression</li>
    <li><a href="https://www.youtube.com/watch?v=nM4dE_IMfhs">Youtube 'Promath' : Formule de la régression linéaire</li>
    <li><a href="https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html">Sickitlearn : mean_absolute_error</li>
    <li><a href="https://dataanalyticspost.com/Lexique/k-means-ou-k-moyennes/#:~:text=K%2Dmeans%20(ou%20K%2Dmoyennes)%20%3A%20C',en%20groupes%20(ou%20clusters).">Data analytics post : K-means algorithm</li>
    <li><a href="https://www.youtube.com/watch?v=4b5d3muPQmA">Youtube 'Statquest' : K-means clustering</li>
      

  <h2>2. Office automation</h2>
    <li><a href="https://openclassrooms.com/fr/courses/5870121-realisez-un-diaporama-pour-accompagner-votre-presentation">Openclassrooms : Réalisez un diaporama pour accompagne votre présentation</a></li>
  
