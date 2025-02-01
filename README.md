<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>S&P 500 Stock Market Prediction</title>
</head>
<body>
    <h1>S&P 500 Stock Market Prediction</h1>

    <h2>Project Overview</h2>
    <p>This project demonstrates a machine learning approach to predicting S&P 500 index price trends using a Random Forest Classifier. The goal is to create a predictive model that can forecast the next day's stock market movement.</p>

    <h2>Key Features</h2>
    <ul>
        <li>Data Source: Yahoo Finance API</li>
        <li>Machine Learning Algorithm: Random Forest Classifier</li>
        <li>Historical Data Range: 1927-2025</li>
        <li>Prediction Target: Daily stock price trend (up or down)</li>
    </ul>

    <h2>Dataset Columns</h2>
    <table>
        <tr>
            <th>Column</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>Index</td>
            <td>Date of trade</td>
        </tr>
        <tr>
            <td>Open</td>
            <td>Opening Price</td>
        </tr>
        <tr>
            <td>High</td>
            <td>Highest Price</td>
        </tr>
        <tr>
            <td>Low</td>
            <td>Lowest Price</td>
        </tr>
        <tr>
            <td>Close</td>
            <td>Closing Price</td>
        </tr>
        <tr>
            <td>Target</td>
            <td>Binary classification (1 = price increase, 0 = price decrease)</td>
        </tr>
    </table>

    <h2>Technical Details</h2>
    <ul>
        <li>Libraries: NumPy, Pandas, Scikit-learn, YFinance</li>
        <li>Prediction Method: Random Forest Classification</li>
        <li>Features: Multiple time-frame trend indicators</li>
    </ul>

    <h2>Disclaimer</h2>
    <p>⚠️ This project is for educational purposes. Past performance does not guarantee future results.</p>
</body>
</html>
