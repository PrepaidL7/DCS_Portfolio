# Actuary

#### Technical Skills: Python, SQL, Scikit-Learn, AzureML

## Education
- B.S., Actuarial Science | Benemerita Universidad Autonoma de Puebla (_2025_)
  
## Work Experience
**Intern @ Emprende Financiera (2024)**  
  
- Supported the data engineering process, including cleaning, preprocessing, and merging large datasets.
- Designed and implemented a logistic regression model to classify credit approval, achieving interpretability of key financial variables and aiding decision making.  
- Developed a random forest model for credit risk assessment, improving prediction accuracy by 5%, with a total precision of 91.58%.  
- Delivered insights and reports for stakeholders, supporting the optimization of financial operations. 
- Prepared executive-level presentations detailing the impact of data-driven financial solutions.

## Impact Projects
### Credit Risk Evaluation with Machine Learning  

- [Repository](https://github.com/PrepaidL7/Credit-Classification-Models)

Developed a comparative analysis of logistic regression and random forest models to evaluate credit risk for microloans, showcasing a balance between interpretability and prediction accuracy.  
- Utilized Python and Scikit-Learn for model building, validation, and feature importance analysis.  
- Presented key findings, such as the impact of specific financial variables on credit approval, demonstrating advanced skills in data manipulation and storytelling.

### Credit Scoring with Machine Learning 

- [Repository](https://github.com/PrepaidL7/Credit-Scoring-PD)

Developed a credit scoring project focused on estimating the probability of default (PD) using logistic regression, with an emphasis on regulatory compliance, interpretability, and practical deployment for microloan portfolios.

- Performed full-cycle data preparation, including missing value imputation, class balancing, and fine/coarse binning of variables using WoE and IV metrics to ensure consistency with Basel II/III scorecard requirements.
- Built logistic regression models in Python using Scikit-Learn and Statsmodels, comparing model performance through AUC, KS, and confusion matrix analyses.
- Scaled model outputs into interpretable scorecards, demonstrating how PD estimates can be translated into operational credit decision tools.
- Highlighted the contribution of key financial and behavioral features to credit outcomes, balancing predictive performance with explainability.
- Designed the project to complement and extend the work in the Credit-Classification-Models repository, adding depth in regulatory scorecard design and PD estimation.

### Macroeconomic Default Modeling and Stress Testing

- [Repository](https://github.com/PrepaidL7/Stress-Testing-IMORA) 

Developed a macroeconomic modeling project aimed at estimating the probability of default (PD) in credit card portfolios using economic indicators and applying stress testing techniques aligned with risk management practices.

- Constructed a logit-based macroeconomic model using monthly data from 2015 to 2024, incorporating over 30 indicators from INEGI and Banxico, including GDP, inflation, employment, interest rates, and external trade figures.
- Applied multiple regression techniques—Ordinary Least Squares, Ridge, Lasso, and Elastic Net—to model the transformed logit(PD) variable, using time-aware cross-validation and lagged variables to respect temporal dependencies.
- Selected Ridge regression as the final model due to its superior generalization performance, optimized via custom RMSE weighting to prioritize prediction accuracy during high-risk periods (PD peaks).
- Interpreted the economic significance of key features such as IGAE, CETES, and import volume, demonstrating how shifts in macroeconomic conditions translate into variations in portfolio-level credit risk.
- Designed and implemented a stress testing framework by simulating adverse scenarios (e.g., interest rate hikes, economic contraction), quantifying their projected impact on default probabilities using the fitted model.
- Produced visual comparisons and quantitative metrics illustrating how macro shocks propagate through the model, increasing estimated PD by up to 1.86 percentage points under a moderate economic downturn.

This project highlights the integration of statistical modeling with economic intuition to support forward-looking credit risk management strategies in financial institutions.


## Tecnical Skills Projects
### Data analysis using The Movie Database (TMDB) 

- [Repository](https://github.com/PrepaidL7/TMDB-MovieInsights)

__[MovieVerse Insights](https://github.com/PrepaidL7/TMDB-MovieInsights/blob/main/Project_01_MovieVerse_Insights.ipynb)__

Developed an in-depth analysis of movie data from the TMDB API to uncover insights on popular movies, genres, and trends.

- Utilized Python, Pandas, and Matplotlib for data wrangling, feature extraction, and data visualization.
- Conducted exploratory data analysis (EDA) to identify patterns in movie ratings, genres, and release dates, highlighting significant trends in movie popularity.
- Presented key insights, such as the relationship between movie genre and rating, showcasing the ability to extract actionable insights from large datasets.

__[API DataRetriever](https://github.com/PrepaidL7/TMDB-MovieInsights/blob/main/Project_01_API_DataRetriever.ipynb)__

Developed a data pipeline to extract, process, and analyze movie data from the TMDb API, leveraging parallel processing to efficiently retrieve large-scale datasets. The project focused on building a comprehensive movie database by extracting detailed film information, which was utilized in the ``Data analysis using The Movie Database (TMDB)`` project.

- Implemented multithreading with Python’s `concurrent.futures` to optimize API requests, reducing data retrieval time while handling potential connection errors and request failures.  
- Utilized Python, Pandas, and JSON processing techniques to clean and structure the extracted data, ensuring consistency and usability for further analysis.  

__[Data Cleaning](https://github.com/PrepaidL7/TMDB-MovieInsights/blob/main/Project_01_DataCleaning.ipynb)__

Developed an in-depth analysis of movie genre data, focusing on extracting and processing structured information from nested data formats.

- Utilized Python and Pandas to clean and process lists of dictionaries, extracting relevant genre information efficiently.
- Applied data transformation techniques to restructure and filter movie genres, ensuring accurate representation and usability.
- Conducted exploratory data analysis (EDA) to identify patterns in genre distributions and isolate specific categories like "Family" for further insights.
- Presented key findings on handling JSON-like data structures, showcasing the ability to extract, filter, and refine information from complex datasets.

__[Merging Movies](https://github.com/PrepaidL7/TMDB-MovieInsights/blob/main/Project_01_Merging_Movies.ipynb)__

Developed a structured data processing workflow to efficiently merge and analyze multiple datasets. 

- Utilized Python and Pandas to merge datasets, handling different join types (inner, outer, left, and right) to ensure data completeness and accuracy.
- Addressed data inconsistencies by resolving duplicate records, handling missing values, and standardizing column formats, improving dataset reliability for analysis.

__[Pandas and SQL](https://github.com/PrepaidL7/TMDB-MovieInsights/blob/main/Project_01_Pandas%26SQL.ipynb)__

Developed an in-depth analysis of movie data by integrating Pandas and SQL.

- Utilized Python, Pandas, and SQLite to process and analyze datasets containing information on movies, genres, production companies, and audience ratings.
- Created and managed an SQLite database, loading multiple datasets into structured tables to enable efficient querying and data retrieval.
- Conducted SQL-based exploratory data analysis (EDA) to extract key insights, including total revenue, average budget, and the impact of movie collections on financial performance.
- Executed complex SQL queries to analyze movie trends, genre distributions, and the relationship between audience ratings and production characteristics.

### California-Housing-ML 

- [Repository](https://github.com/PrepaidL7/California-Housing-ML)

__[EDA, Preprocesamiento, ML](https://github.com/PrepaidL7/California-Housing-ML/blob/main/Project_02_EDA_Prepros%26ML.ipynb)__

Developed an in-depth analysis of housing data to identify key patterns and trends in property prices.

- Utilized *Python, Pandas, and Matplotlib* for data cleaning, feature extraction, and visualization of relevant insights.
- Conducted *Exploratory Data Analysis (EDA)* to examine variable distributions, detect outliers, and assess correlations between dataset features.
- Implemented *data preprocessing techniques*, including handling missing values and normalizing variables, ensuring the dataset was suitable for machine learning models.
- Generated key visualizations, such as histograms and correlation heatmaps, to identify relationships between variables like median income and median house value.
- Developed and improved a Random Forest model, fine-tuning hyperparameters and evaluating performance using cross-validation techniques to increase predictive accuracy and reduce overfitting.

## Talks & Lectures
- Modelos de machine learning de clasificación aplicados a un caso de estudio de microcrédito - XVII SIEP Seminar, Fall 2024

## Publications
1. Trejo Cortés, J. A., Hernandez Prado, E. X., Mendoza Rebollar, A., de Jesús Mendoza, V. M., & Cardeña Sosa, D. (2022). Calculadora dinámica de portafolios de inversión. Revista del Colegio Nacional de Actuarios, (12), Julio. Derechos reservados © 2022. Recuperado de [https://www.anahuac.mx/mexico/EscuelasyFacultades/actuaria/sites/default/files/inline-files/CONAC-2022-jun.pdf](https://www.anahuac.mx/mexico/EscuelasyFacultades/actuaria/sites/default/files/inline-files/CONAC-2022-jun.pdf)
2. Cardeña Sosa, D., Juárez Hernández, B., & Vázquez Guevara, V. H. (2024). Modelos de machine learning de clasificación aplicados a un caso de estudio de microcrédito. Presentado en la XVII Semana Internacional de la Estadística y la Probabilidad, FCFM-BUAP, Puebla, México. Recuperado de [https://www.fcfm.buap.mx/SIEP/2024/MEMORIAS_XVIISIEP_2024.pdf](https://www.fcfm.buap.mx/SIEP/2024/MEMORIAS_XVIISIEP_2024.pdf)
3. Cardeña Sosa, D. (2024). Aplicación de modelos predictivos en la evaluación de solicitudes de crédito: un estudio comparativo (Tesis de Licenciatura). Benemérita Universidad Autónoma de Puebla, Puebla, México. Dirigida por Dr. Bulmaro Juárez Hernández.
