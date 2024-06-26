<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Revenue Prediction</title>
</head>
<body>

<h1>Restaurant Revenue Prediction</h1>

<p>This project aims to predict the revenue of restaurants based on various features such as franchise status, category, number of items, and orders placed. The project involves data preprocessing, visualization, and applying machine learning algorithms for prediction.</p>

<h2>Dataset Attributes</h2>
<ul>
    <li><strong>ID:</strong> Restaurant ID</li>
    <li><strong>Name:</strong> Name of the Restaurant</li>
    <li><strong>Franchise:</strong> Restaurant has franchise or not</li>
    <li><strong>Category:</strong> Specific type of category provided by the restaurant</li>
    <li><strong>No_of_item:</strong> Different types of items provided by the restaurant</li>
    <li><strong>Order_Placed:</strong> Order placed by customer to restaurant (in lacs)</li>
    <li><strong>Revenue:</strong> Total amount of income generated by the restaurant</li>
</ul>

<h2>Project Tasks</h2>
<ol>
    <li>Check for null values and duplicacy in the dataset.</li>
    <li>Remove unwanted columns.</li>
    <li>Encode categorical columns.</li>
    <li>Perform data visualization to understand the relationships between variables.</li>
    <li>Apply machine learning algorithms to predict restaurant revenue.</li>
</ol>

<h2>Data Visualization</h2>
<p>The data visualization includes:</p>
<ul>
    <li>Pairplot to see relationships between features.</li>
    <li>Heatmap to visualize correlations between features.</li>
    <li>Distribution plot of revenue.</li>
    <li>Boxplots to visualize revenue distribution by category and franchise status.</li>
</ul>

<h2>Machine Learning Models</h2>
<p>Two machine learning models were used for prediction:</p>
<ul>
    <li>Linear Regression</li>
    <li>Random Forest Regression</li>
</ul>
<p>The performance of both models was evaluated using Mean Squared Error (MSE) and R-squared (R2) metrics.</p>

<h2>Code Structure</h2>
<pre>
├── restaurant_data.csv
├── main.py
└── README.html
</pre>

<h2>How to Run</h2>
<ol>
    <li>Clone the repository.</li>
    <li>Ensure you have the required libraries installed. You can install them using:
        <pre><code>pip install pandas numpy matplotlib seaborn scikit-learn</code></pre>
    </li>
    <li>Run the <code>main.py</code> script to execute the project.</li>
</ol>

<h2>Example Prediction</h2>
<p>An example prediction can be made by providing specific values for features such as franchise status, category, number of items, and orders placed.</p>

<h2>Conclusion</h2>
<p>This project demonstrates the process of predicting restaurant revenue using machine learning models. It involves data preprocessing, visualization, and model evaluation to achieve the desired predictions.</p>

</body>
</html>
