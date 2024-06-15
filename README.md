# Sentiment Analyzer

The Sentiment Analyzer is a Flask based web application that allows users to analyze the sentiment of text, comments, or reviews. It uses natural language processing techniques to classify the sentiment as positive, negative, or neutral. The model has achieved an accuracy of 93.05% using the Gradient Boosting Classifier.

## Screenshots
<table>
  <tr>
    <td>
      <img src="https://github.com/Bratajit-03/Sentiment-Analyzer/assets/106532791/74d03bd4-ca6b-4588-9073-1a6f96e2d50c" alt="Home Page" width="500" height="300"/>
    </td>
    <td>
      <img src="https://github.com/Bratajit-03/Sentiment-Analyzer/assets/106532791/c65d2889-1900-4f84-85aa-d0c39ceea440" alt="Result Page" width="500" height="300"/>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Home Page</b></td>
    <td align="center"><b>Result Page</b></td>
  </tr>
</table>

## How to Run
1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/sentiment-analyzer.git
    cd sentiment-analyzer
    ```

2. **Create a virtual environment and activate it**:
    ```sh
    python -m venv venv
    source venv/bin/activate  
    ```

3. **Install the dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```sh
    flask run
    ```

5. **Open your web browser and visit**:
    ```
    http://127.0.0.1:5000/
    ```

## Dataset Availability
The dataset used for training the sentiment analysis model is taken from [Kaggle](https://www.kaggle.com/datasets/niraliivaghani/flipkart-product-customer-reviews-dataset)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
