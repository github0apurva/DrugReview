# DrugReview
Sentiment classification for drug review data from UCI archive


DrugReview.ipynb - Contains only the EDA part


DrugReview_co.ipynb - Contains the data pre processing till now.


Changes from the last time (repository DrugReview_NN).

	1. Data load directly from website
	2. Better EDA
	3. Clubbed default values with condition variable
	4. condition & drugname : 
		a. first clustering for groups based on rating distribution 
		b. and then creating dummy for the clusters
	5. Remove missing condition rows
	6. Using these variables in models: Usefulcount, year, month & weekday 
	7. Handling various errors in spelling 
		a. Repeated alphabets 
		b. Spelling errors 							No
		c. Space error								No
		d. No Space between number and text					No
	8. Added section for understanding
		a. Vocab size 
		b. Vocab freq  and 
		c. Distribution of reviews length
	9. Working in colab to incorporate glove embedding				Not yet
	10. Resampling for equal rating distribution					Not yet
	
	TYpes of model:
	1. dependent as regressor,  simple network with only text       input and no embedding		Done
	2. dependent as regressor,  simple network with only text       input and    embedding
	3. dependent as regressor, complex network with only text       input and    embedding
	4. dependent as regressor, complex network with      text & aux input and    embedding	
	
	
	
	
	
	
	
