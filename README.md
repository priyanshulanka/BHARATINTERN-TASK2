<!DOCTYPE html>
<html lang="en">
    
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="temperature-thermometer-removebg-preview.png" sizes= "64×64 " type="img/png">
    <title>Temperature convertor</title>
</head>
<body>
    <br>
    <h1 style="background-color: #DAEAF1; color: black;"> Application to convert Temperature from &#176;Celsius to &#176;Fahrenheit </h1>
    <br>
    <div class="container">
        <form id="calcTemp" onsubmit = "calculateTemp(); return false">
            <label for="temp">Enter the temperature to be converted</label>
            <br>
            <input type="number" name="temp" id="temp" value="0">
            <select name="temp_diff" id="temp_diff">
                <option value="cel" id="option">&#176;Celsius</option>
                <option value="fah" id="option">&#176;Fahrenheit</option>
            </select>
            <br>
            <input type="submit" name="temp" id="submit">
            <br>
            <span id="result"></span>
        </form>
    </div>
    <script src="script.js"></script>
</body>
</html>
