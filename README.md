<!DOCTYPE html>
<html>
<head>
  <title>Cryptocurrency Prices</title>
  <link rel="stylesheet" href="style.css"> 
</head>
<body>

  <header>
    <h1>Cryptocurrency Prices</h1>
  </header>

  <section class="container">
    <table>
      <thead>
        <tr>
          <th>Name</th>
          <th>Symbol</th>
          <th>Price (USD)</th>
          <th>24h Change</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Bitcoin</td>
          <td>BTC</td>
          <td><span class="price">$96,000</span></td> 
          <td><span class="price">+1.5%</span></td>
        </tr>
        <tr>
          <td>Ethereum</td>
          <td>ETH</td>
          <td><span class="price">$3196</span></td>
          <td><span class="price-down">-0.8%</span></td>
        </tr>
        <tr>
          <td>Dogecoin</td>
          <td>DOGE</td>
          <td><span class="price">$0.06</span></td>
          <td><span class="price">-0.2%</span></td>
        </tr>
      </tbody>
    </table>
  </section>

</body>
</html> <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 25px;
      background-color: #f0f0f0;
    }

   header {
      text-align: center;
      padding: 25px;
      background-color: #333;
      color: #fff;
    }

   h1 {
      margin: 0;
    }

  section {
      margin: 25px 0;
    }

  .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 25px;
      background-color: #fff;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

   table {
      width: 100%;
      border-collapse: collapse;
    }

   th, td {
      border: 1px solid #ddd;
      padding: 10px;
      text-align: left;
    }

  th {
      background-color: #f2f2f2;
    }

  .price {
      color: #009688;
    }

  .price-down {
      color: #f44336;
    }
  </style>  
