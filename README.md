<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Order Invoice</title>

<style>
    body {
        font-family: Arial, sans-serif;
        background: #f0f0f0;
        padding: 20px;
    }

    table {
        width: 80%;
        margin: auto;
        border: 2px solid #000;
        border-collapse: collapse;
        background: #fff;
    }

    th, td {
        border: 1px solid #000;
        padding: 10px;
        font-size: 16px;
    }

    th {
        background: #eaeaea;
        font-weight: bold;
    }

    .center {
        text-align: center;
        font-size: 18px;
        background: #eaeaea;
        font-weight: bold;
    }

    .total-row td {
        font-weight: bold;
    }
</style>
</head>
<body>

<table>

    <!-- Order Info -->
    <tr>
        <th>Order no:</th>
        <td>#XYZ789</td>
    </tr>

    <tr>
        <th>Order Date:</th>
        <td>05-Dec-2025</td>
    </tr>

    <!-- Customer Section -->
    <tr>
        <td colspan="2" class="center">Customer</td>
    </tr>

    <tr>
        <th>Name:</th>
        <td>Rohit Singh</td>
    </tr>

    <tr>
        <th>Address:</th>
        <td>ahmedabad,Gota,380081</td>
    </tr>

    <!-- Order Details Header -->
    <tr>
        <td colspan="4" class="center">Order Details</td>
    </tr>

    <tr>
        <th>#</th>
        <th>Item</th>
        <th>Type</th>
        <th>Price</th>
    </tr>

    <tr>
        <td>1</td>
        <td>Wireless charger</td>
        <td>Electronics</td>
        <td>25.00€</td>
    </tr>

    <tr>
        <td>2</td>
        <td>white paint</td>
        <td>Home Decor</td>
        <td>100.00€</td>
    </tr>

    <tr>
        <td>3</td>
        <td>Coffee machine</td>
        <td>Appliances</td>
        <td>250.00€</td>
    </tr>

    <tr>
        <td>4</td>
        <td>Fitness Tracker</td>
        <td>Wearable</td>
        <td>49.00€</td>
    </tr>

    <!-- Total -->
    <tr class="total-row">
        <td colspan="3" style="text-align:right;">Total:</td>
        <td>424.00€</td>
    </tr>

</table>

</body>
</html>
