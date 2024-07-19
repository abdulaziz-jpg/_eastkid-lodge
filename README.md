<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Lodge Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        .container {
            padding: 2em;
            max-width: 800px;
            margin: auto;
        }
        .room {
            border: 1px solid #ccc;
            border-radius: 10px;
            padding: 1em;
            margin-bottom: 1em;
            background-color: white;
        }
        .room h2 {
            margin-top: 0;
        }
        .room p {
            margin: 0.5em 0;
        }
        .price {
            color: green;
            font-weight: bold;
        }
        form {
            background-color: white;
            padding: 2em;
            border-radius: 10px;
            border: 1px solid #ccc;
        }
        form input, form textarea {
            width: 100%;
            padding: 0.5em;
            margin-bottom: 1em;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 1em;
        }
        form input[type="submit"]:hover {
            background-color: #45a049;
        }
        footer {
    background: #333333;
    color: #fff;
    text-align: center;
    padding: 0%;
    position: fixed;
    width: 100%;
    bottom: 0;
}
    </style>
</head>
<body>
    <header>
        <h1>Welcome to _eastkid Lodge</h1>
        <p>Experience the best stay at affordable prices</p>
    </header>
    <div class="container">
        <div class="room">
            <h2>Standard Room</h2>
            <p>Comfortable and cozy room with all the necessary amenities.</p>
            <p class="price">120000Tsh per night</p>
        </div>
        <div class="room">
            <h2>Deluxe Room</h2>
            <p>Spacious room with additional features and a beautiful view.</p>
            <p class="price">150000Tsh per night</p>
        </div>
        <div class="room">
            <h2>Suite</h2>
            <p>Luxurious suite with separate living area and premium amenities.</p>
            <p class="price">20000Tsh per night</p>
        </div>
        <form action="your_form_processing_url" method="post">
            <h2>Send a Request</h2>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="days">Number of Days:</label>
            <input type="number" id="days" name="days" required>
            <label for="room">Room Type:</label>
            <select id="room" name="room">
                <option value="standard">Standard Room</option>
                <option value="deluxe">Deluxe Room</option>
                <option value="suite">Suite</option>
            </select>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4"></textarea>
            <input type="submit" value="Send Request">
        </form>
    </div>
</body>

</html>
