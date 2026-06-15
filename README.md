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
    <p class="tagline">Watch the World Create</p>

    <div class="auth-box">

      <h2>Login</h2>

      <label>Email</label>
      <input type="text" placeholder="Enter your email">

      <label>Password</label>
      <input type="password" placeholder="Enter your password">

      <button class="btn">LOG IN</button>

      <p class="switch">Don’t have an account? <span>Sign Up</span></p>

    </div>

  </div>

</body>
</html>
body {
  margin: 0;
  font-family: Arial;
  background: linear-gradient(135deg, #000000, #00ff66);
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
}

.container {
  text-align: center;
}

.logo {
  color: #00ff66;
  font-size: 55px;
  letter-spacing: 4px;
}

.tagline {
  opacity: 0.8;
  margin-bottom: 20px;
}

.auth-box {
  background: rgba(0,0,0,0.75);
  padding: 25px;
  border-radius: 12px;
  width: 300px;
  box-shadow: 0 0 20px #00ff66;
}

label {
  display: block;
  text-align: left;
  margin-top: 10px;
  font-size: 13px;
  opacity: 0.8;
}

input {
  width: 100%;
  padding: 10px;
  margin-top: 5px;
  border: none;
  border-radius: 6px;
}

.btn {
  width: 100%;
  margin-top: 15px;
  padding: 10px;
  background: #00ff66;
  border: none;
  font-weight: bold;
  cursor: pointer;
  border-radius: 6px;
}

.switch {
  margin-top: 15px;
  font-size: 13px;
}

.switch span {
  color: #00ff66;
  cursor: pointer;
  
}
