
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Enter Your Name</title>
  <style>
    * {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  text-align: center;
  padding-top: 50px;
  font-family: Arial, sans-serif;
  background: linear-gradient(to right, #ffdde1, #ee9ca7);
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

h2 {
  font-size: 24px;
  margin-bottom: 20px;
  color: black;
}

form {
  width: 90%;
  max-width: 400px;
  background: #fff;
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

label {
  font-size: 18px;
  display: block;
  margin-bottom: 10px;
  color: #444;
  text-align: left;
}

input[type="text"] {
  width: 100%;
  padding: 10px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 6px;
  margin-bottom: 20px;
}

button {
  width: 100%;
  padding: 10px;
  font-size: 16px;
  background-color: #ff4081;
  color: white;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #e91e63;
}

/* 📱 Mobile-specific styles */
@media screen and (max-width: 480px) {
  body {
    padding: 20px 10px;
    padding-top: 40px;
  }

  h2 {
    font-size: 20px;
  }

  label {
    font-size: 16px;
  }

  input[type="text"] {
    font-size: 15px;
    padding: 8px;
  }

  button {
    font-size: 15px;
    padding: 8px;
  }
}

  </style>
</head>
<body>
  <h2>🤩 Welcome to the Birthday Surprise 🎉</h2>
  <form action="./whisese/index.html" method="GET">
    <label for="name">What's your Beautiful name?</label>
    <input type="text" id="name" name="name" required>
    <button type="submit">OK</button>
  </form>
</body>
</html>
