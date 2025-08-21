<!DOCTYPE html>
<html>
<head>
    <title>Logic Page</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #f5f5f5;
            font-family: Arial, sans-serif;
        }

        .logic-box {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0,0,0,0.2);
            text-align: center;
            width: 300px;
        }

        .logic-box h2 {
            margin-bottom: 20px;
        }

        .logic-box input {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .logic-box button {
            width: 100%;
            padding: 10px;
            background: blue;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        .logic-box button:hover {
            background: darkblue;
        }

        .logic-box p {
            margin-top: 15px;
            font-size: 14px;
        }

        .logic-box a {
            color: blue;
            text-decoration: none;
        }

        .logic-box a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="logic-box">
        <h2>Logic</h2>
        <form>
            <input type="text" placeholder="Username" required> 
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
            <p>Don't have an account? <a href="#">Sign up</a></p>
        </form>
    </div>
</body>
</html>
