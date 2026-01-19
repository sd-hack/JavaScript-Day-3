# JavaScript-Day-3
<!DOCTYPE html>
<html>
<head>
  <title>Tony’s Café Inventory</title>
</head>

<body>

  <h2>📋 Tony’s Café Inventory Display</h2>

  <p id="output"></p>

  <script>
    // 1. Cafe details (filled values)
    let cafeName = "Tony’s Café";
    let itemPrice = 200;
    let isAvailable = true;
    let specialDish;      // undefined
    let discount = null;  // null

    // 2. Show values and their data types on page
    document.getElementById("output").innerHTML =
      "Cafe Name: " + cafeName + " (Type: " + typeof cafeName + ")<br><br>" +
      "Item Price: " + itemPrice + " (Type: " + typeof itemPrice + ")<br><br>" +
      "Available: " + isAvailable + " (Type: " + typeof isAvailable + ")<br><br>" +
      "Special Dish: " + specialDish + " (Type: " + typeof specialDish + ")<br><br>" +
      "Discount: " + discount + " (Type: " + typeof discount + ")";
  </script>

</body>
</html>
