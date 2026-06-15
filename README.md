
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>VIOLEX</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <div class="container">

    <h1 class="logo">VIOLEX</h1>
    <p>Watch the World Create</p>

    <input placeholder="Email">
    <input type="password" placeholder="Password">

    <button>LOG IN</button>

  </div>

  <script src="script.js"></script>
</body>
</html>
body {
  margin: 0;
  font-family: Arial;
  background: linear-gradient(135deg, black, #00ff66);
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
}

.logo {
  color: #00ff66;
  font-size: 50px;
  letter-spacing: 3px;
}

input {
  display: block;
  margin: 10px auto;
  padding: 10px;
  width: 220px;
}

button {
  padding: 10px;
  width: 240px;
  background: #00ff66;
  border: none;
  cursor: pointer;
}
console.log("Violex is running");
