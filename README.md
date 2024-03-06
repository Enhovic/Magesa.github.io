
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contact Form</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        margin: 0;
        padding: 0;
    }

    h1{
        text-align: center;
        font-size: 45px;
    } 

    .container {
        max-width: 400px;
        margin: 50px auto;
        padding: 20px;
        background-color: #fff;
        border-radius: 5px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    input[type="text"], input[type="email"], input[type="tel"], input[type="submit"], input[type="Cancel"] {
        width: 100%;
        padding: 10px;
        margin-bottom: 18px;
        box-sizing: border-box;
        border: 1px solid #ccc;
        border-radius: 4px;
        border-color: #2f00ff;

    }
    input[type="submit"] {
        background-color: #2f00ff;
        color: white;
        cursor: pointer;
    }
    input[type="submit"]:hover {
        background-color: #45a049;
    }
    input[type="Cancel"] {
        background-color: #45a049;
        color: white;
        cursor: pointer;
        text-align: center;
        
    }
    input[type="Cancel"]:hover {
        background-color: #2f00ff;
    }
</style>
</head>
<body>
    <h1>Contact Us</h1>
<div class="container">
    
    <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="subject">Subject:</label>
        <input type="text" id="subject" name="subject" required>
        
        <input type="submit" value="Submit">
        <input type="Cancel" value="Cancel">
    </form>
</div>
</body>
</html>

