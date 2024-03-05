# Vietnamese-Reviews-Classification-using-NN
The goal of this project is to build a Neural Network model that can classify vietnamese reviews as Postive or Negative.
## Project overview
### 1. Dataset
- The NTC-SCV dataset contains 50000 reviews, with 30000 reviews use for training and 10000 reviews use for testing. Each review can be Positve or Negative.
### 2. Data pre-processing
- Remove reviews that are not Vietnamese.
- Remove HTML tags and URL in the review.
- Remove punctuation and number in review.
- Remove special character and icon
- Normalize the white space.
- Lowercase the review.
### 3. Text Representation
- Tokenize the reviews using word-based tokenizer.
- Build vocabulary from the reviews.
- Represent the reviews as Dense Vectors
### 4. Model building and training
- Build a Neural Network with 2 layers: EmbeddingBag Layer and Linear Layer
- Train the Network with Cross Entropy Loss and SGD optimizer.
### 5. Predicting and Evaluating
- Define a Predict function.
- Evaluate the model performance using Accuracy Score.
