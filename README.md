<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Create Account Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: blue;
            margin: 0;
            padding: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        
        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            width: 100%;
        }

        label {
            display: block;
            margin-bottom: 8px;
        }

        input {
            width: 100%;
            padding: 8px;
            margin-bottom: 16px;
            box-sizing: border-box;
        }

        button {
            background-color: blue;
            color: #fff;
            padding: 16px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }

        button:hover {
            background-color: #45a049;
        }

        .remember-me {
            margin-bottom: 8px;
        }
    </style>
</head>
<body>
    
    <form action="#" method="post">
        <h1><center>Create Account</center></h1>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>

        <div class="remember-me">
        <input type="checkbox" id="remember" name="remember" >
        <label for="remember">Remember me</label>
        
        </div>

        <button type="submit">Sign Up</button>
        <center><p>Already have an account?<a href="#">Login</center></a></p>
    </form>

   

</body>
</html>
