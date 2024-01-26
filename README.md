# Analyze_real_estate_prices_evolution_with_Python

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
