# FullWeb
First web 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
    <style>
        * {
            box-sizing: border-box;
            /* Ensures padding and border are included in the element's total width and height */
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #1a1a1a;
            /* Darker background for better contrast */
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .card {
            padding: 30px;
            border: none;
            width: 300px;
            border-radius: 15px;
            background-color: #f9f9f9;
            /* Light background for the card */
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            /* Subtle shadow for depth */
            text-align: center;
        }

        h1 {
            color: #333;
            /* Darker heading color */
            margin-bottom: 20px;
            font-size: 24px;
            /* Increased font size for heading */
        }

        .email {
            width: 100%;
            /* Full width input fields */
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            /* Light border */
            border-radius: 9px;
            font-size: 16px;
            /* Increased font size for better readability */
            transition: border-color 0.3s;
            /* Smooth transition for border color */
        }

        .email:focus {
            border-color: #007bff;
            /* Change border color on focus */
            outline: none;
            /* Remove default outline */
        }

        .button {
            width: 100%;
            /* Full width button */
            background-color: #007bff;
            /* Bootstrap primary color */
            color: white;
            /* White text color */
            padding: 10px;
            border: none;
            /* No border */
            border-radius: 9px;
            font-size: 16px;
            /* Increased font size */
            cursor: pointer;
            /* Pointer cursor on hover */
            transition: background-color 0.3s;
            /* Smooth transition for background color */
        }

        .button:hover {
            background-color: #0056b3;
            /* Darker shade on hover */
        }

        .footer {
            margin-top: 20px;
            /* Space for footer */
            font-size: 14px;
            /* Smaller font size for footer */
            color: #666;
            /* Grey color for footer text */
        }
    </style>
</head>

<body>
    <div class="card">
        <h1>Login</h1>
        <label for="email">
            <input id="email" class="email" type="text" placeholder="Email" required>
        </label>
        <label for="password">
            <input id="password" class="email" type="password" placeholder="Password" required>
        </label>
        <button class="button" type="submit">Login</button>
        <div class="footer">Don't have an account? <a href="#" style="color: #007bff;">Sign up</a></div>
    </div>
</body>

</html>
