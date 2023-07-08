<!DOCTYPE html>
<html lang="en">
    
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="VOTE ELIGIBLITY.png" sizes= "64×64 " type="img/png">
    <title>Temperature convertor</title>
</head>
<body>
    <br>
    <h1 style="background-color: #DAEAF1; color: black;"> Application to check the vote eligibility from age &#176;ADULT/STATUS/AGE/GENDER / YOUTH&#176; </h1>
    <br>
    <div class="container">
        <form id="agetemt" onsubmit = "calculateTemp(); return false">
            <label for="temp">Enter the temperature to be converted</label>
            <br>
            <input type="number" name="age" id="age" value="0">
            <select name="temp_diff" id="temp_diff">
                <option value="ADULT" id="option">&#176;ADULT</option>
                <option value="STATUS" id="option">&#176;STATUS</option>
                <option value="AGE" id="option">&#176;AGE</option>
                <option value="GENDER" id="option">&#176;GENDER</option>
                <option value="YOUTH" id="option">&#176;YOUTH</option>
                
                
            </select>
            <br>
            <input type="submit" name="age" id="submit">
            <br>
            <span id="result"></span>
        </form>
    </div>
    <script src="script.js"></script>
</body>
</html>
