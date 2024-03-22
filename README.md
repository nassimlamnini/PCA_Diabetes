<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PCA Analysis on Diabetes Dataset</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 0;
            background: #f4f4f4;
            color: #333;
        }
        h1, h2, h3 {
            color: #333;
        }
        .content {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        code {
            background: #eee;
            padding: 2px 4px;
            border-radius: 4px;
            font-family: 'Courier New', Courier, monospace;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>PCA Analysis on Diabetes Dataset</h1>
        <p>This repository contains a Jupyter Notebook which performs a Principal Component Analysis (PCA) on the diabetes dataset provided by <code>sklearn</code>.</p>

        <h2>Objective</h2>
        <p>The objective of this analysis is to reduce the dimensionality of the dataset while preserving as much variability as possible. This is achieved by transforming the data to a new set of variables, the principal components, which are uncorrelated and ordered so that the first few retain most of the variation present in all of the original variables.</p>

        <h2>Results</h2>
        <p>The analysis results in a selection of principal components that effectively capture the significant information of the dataset. The accompanying plots illustrate the variance explained by each component and the data distribution along these components.</p>

        <h2>Usage</h2>
        <p>To run this analysis, clone the repository and execute the Jupyter Notebook. Ensure that you have <code>pandas</code>, <code>numpy</code>, <code>matplotlib</code>, <code>sklearn</code>, and <code>jupyter</code> installed in your Python environment.</p>

        <h2>Contribution</h2>
        <p>Contributions are welcome! Please fork this repository and submit a pull request with your suggested changes.</p>
    </div>
</body>
</html>
