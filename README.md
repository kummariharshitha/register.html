# register.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Animated Login Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

 <section>
     <div class="login-box">
          <form action="">
              <h2>Login</h2>
              <div class="input-box">
                  <span class="icon">
                      <ion-icon name="mail-outline"></ion-icon>       
                  </span>
                  <input type="email" required>
                  <label>Email</label>
              </div>
              <div class="input-box">
                  <span class="icon">
                      <ion-icon name="lock-closed-outline"></ion-icon>
                  </span>
                  <input type="Password" required>
                  <label>Password</label>
              </div>
              <div class="remember-forgot">
                  <label><input type="checkbox">Remember me</label>
                  <a href="#">Forgot Password?</a>
              </div>
              <button type="submit">Login</button>
              <div class="register-link">
                 <p>Don't have an account? <a href="#">Register</a></p>
              </div>
          </form>
       </div>
 </section>   
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
</body>
</html>
