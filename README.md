<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SHREE SHAKTI AMUL STOCK</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 20px;
    }
    h1 {
      color: red;
      margin-bottom: 5px;
    }
    #date {
      margin-bottom: 20px;
      font-weight: bold;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 20px;
    }
    th {
      background: #000;
      color: white;
      padding: 8px;
    }
    td {
      border: 1px solid #ccc;
      padding: 6px;
    }
    input {
      width: 90%;
      padding: 5px;
      text-align: center;
    }
    button {
      padding: 10px 20px;
      margin: 10px;
      background: red;
      color: white;
      border: none;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background: darkred;
    }
  </style>
</head>
<body>

  <h1>SHREE SHAKTI AMUL STOCK</h1>
  <div id="date"></div>

  <table>
    <tr>
      <th>Product</th>
      <th>Carat</th>
      <th>Nang</th>
    </tr>
    <!-- 11 Rows -->
    <tr>
      <td><input type="text" placeholder="Product 1"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
    <tr>
      <td><input type="text" placeholder="Product 2"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
    <tr>
      <td><input type="text" placeholder="Product 3"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
    <tr>
      <td><input type="text" placeholder="Product 4"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
    <tr>
      <td><input type="text" placeholder="Product 5"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
    <tr>
      <td><input type="text" placeholder="Product 6"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
    <tr>
      <td><input type="text" placeholder="Product 7"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
    <tr>
      <td><input type="text" placeholder="Product 8"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
    <tr>
      <td><input type="text" placeholder="Product 9"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
    <tr>
      <td><input type="text" placeholder="Product 10"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
    <tr>
      <td><input type="text" placeholder="Product 11"></td>
      <td><input type="text" placeholder="Carat"></td>
      <td><input type="text" placeholder="Nang"></td>
    </tr>
  </table>

  <button onclick="resetForm()">Reset</button>

  <script>
    // Auto Date DD/MM/YYYY
    const today = new Date();
    const date = today.getDate().toString().padStart(2, '0') + '/' + 
                 (today.getMonth() + 1).toString().padStart(2, '0') + '/' + 
                 today.getFullYear();
    document.getElementById("date").innerText = date;

    // Reset Function
    function resetForm() {
      document.querySelectorAll("input").forEach(input => input.value = "");
    }
  </script>

</body>
</html>
