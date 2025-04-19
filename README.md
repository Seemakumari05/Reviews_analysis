# Reviews_analysis

This project focuses on analyzing textual customer reviews to predict numerical ratings using machine learning techniques.It applies natural language processing (NLP) to preprocess raw text as numerical features and a regression model to assess review text's explainability or usability in predicting users' ratings.

This project involves analyzing customer reviews from various languages using a self-curated multilingual dataset. The dataset includes two columns:
 1) Review_Text: Customer reviews in diverse languages (e.g., English, Hindi, Telugu)
 2) Rating: Corresponding numerical ratings (e.g., 1.0 to 5.0)

The primary aim was to investigate how accurately a machine learning model can predict user ratings from multilingual review text.

Key Steps:

 [1] Text Preprocessing: Processed multilingual text with TfidfVectorizer, which has basic multilingual tokenization.

 [2] Model Training: Trained a Linear Regression model to predict Rating values from review text.

 [3] Evaluation: The accuracy of the model was evaluated using Mean Squared Error (MSE) and R-squared (R²) metrics.

 [4] Visualization: Graphs were utilized to compare actual vs predicted ratings and model performance on train/test sets.
