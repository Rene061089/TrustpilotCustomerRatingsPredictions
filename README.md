### Program Description: Customer Rating Prediction

This Python program utilizes machine learning techniques to predict customer ratings for various types of products. The system is designed to analyze historical customer data, considering factors such as product features, previous ratings, and customer preferences.

Key Features:

	1. Data Analysis: The program begins by conducting in-depth data analysis on a dataset containing historical customer reviews and product information.

 	2. Feature Engineering: Relevant features are identified and engineered to enhance the predictive model's accuracy. This may include aspects like product specifications, customer demographics, and sentiment analysis.

  	3. Machine Learning Model: A machine learning model, such as a regression or recommendation algorithm, is trained on the preprocessed data. The model learns patterns and correlations within the data to make accurate predictions.

   	4. Cross-Validation: To ensure the model's robustness, cross-validation techniques are employed to assess its performance on different subsets of the data.

    	5. User Interface: The program may include a user-friendly interface where users can input product details, and the system will provide a predicted customer rating.

     	6. Scalability: The model is designed to handle predictions for a variety of products, making it scalable for diverse industries.

In the project I have:

	1. Gathered data through web scraping and performed cleaning and filtering processes to ensure data quality.
		
	2. Conducted training and comparison of the fastText and Sklearn models on the same dataset to determine which model exhibits higher accuracy.
	
	3. Evaluated and determined the utility of the chosen model by comparing training data with validation data, assessing its performance and generalization capabilities.
 
	4. Used the trained model to predict and compare Trustpilot's current ratings of reviews, providing insights into the model's applicability to real-world data.

	5. Visualized the relationship between the rating and review in a feature space, offering a comprehensive understanding of the data distribution.

	6. Utilized WordCloud analysis to conclude which words are most prominent for each rating category, shedding light on the recurring themes in reviews.
    
#### List of used technologies

	Common
	 - Regular Expressions (RE)
	 - Tabulate
	 - ThreadPoolExecutor
	 - Time
	 - tqdm (ProgressBar)
	
	Data Analysis
	 - Pandas

	Files
	 - Glob
	 - Pickle
	
	Math
	 - Random
	 - Numpy

	Plot
	 - matplotlib
	
	Webscraping
	 - BeautifulSoup (BS4)
	 - Request
	
	Machine learning
	 - FastText
	 - Natural Language Toolkit (NLTK)
	 - Scikit-learn (Sklearn)
	 - WordCloud


#### Installation Guide
   The project is configured to run in Jupyter Notebook. Follow the steps below to set up the environment:
    
### User guide
### run the project in chronological order, follow these steps:
 
	00_install:
	Run the notebook 00_install.ipynb to install necessary packages. Execute the cells in order to set up the environment.
 
 	01_webscraping_request:
	Execute the cells in the notebook 01_webscraping_request.ipynb to perform web scraping using requests.

	01a_webscraping_clean:
	Run the notebook 01a_webscraping_clean.ipynb to clean and preprocess the scraped data.

	02_models:
 	Execute the cells in the notebook 02_models.ipynb to train and compare the fastText and Sklearn models.

	03_evaluate_fasttext:
	Run the notebook 03_evaluate_fasttext.ipynb to evaluate and determine the utility of the chosen model.

	04_predict_rating:
	Execute the cells in the notebook 04_predict_rating.ipynb to predict and compare Trustpilot's current ratings using the trained model.

	05_feature_space:
	Run the notebook 05_feature_space.ipynb to visualize the relationship between rating and review in a feature space.

	06_wordcloud:
	Execute the cells in the notebook 06_wordcloud.ipynb to apply WordCloud analysis and conclude prominent words for each rating.
    
