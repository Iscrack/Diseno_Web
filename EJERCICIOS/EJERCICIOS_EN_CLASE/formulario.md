![image](https://user-images.githubusercontent.com/91554777/170103427-2b681a6e-05b6-49f3-834b-c188ebf12fbb.png)

<!DOCTYPE html>
<html lang="en">
<head>
    <title>FORMULARIO</title>
</head>
<body>
    <h1>Formato de registro</h1>   
       <form action="https://formspree.io/f/{form_id}" method="post">
        <fieldset>
            <legend>Información personal del usuario</legend>
        <label for="name">Introduce tu nombre completo</label><br>
        <input type="text" name="name" id="name"><br>
        <label for="email">Introduce tu email</label><br>
        <input type="mail" name="email" id="email"><br>
        <label for="pasword">Introduce tu contraseña</label><br>
        <input type="pasword" name="pasword" id="pasword"><br>
        <label for="pasword2">Confirma tu contraseña</label><br>
        <input type="pasword" name="pasword2" id="pasword2">
        
        <p>Género</p>  
        <input type="radio" id="gender1" name="gender" value="male"/>
        <label for="gender1">Masculino</label><br>
        <input type="radio" id="gender2" name="gender" value="female"/>
        <label for="gender2">Femenino</label><br>
        <input type="radio" id="gender3" name="gender" value="other"/>
        <label for="gender3">Otro</label><br>
               

        <label for="fill">Introduce tu dirección:</label><br>
        <textarea name="fill" id="fill" cols="30" rows="05"></textarea><br>
        <input type="submit" id="submit" value="Registrarse">    
       </fieldset>   
    </form>
        
</body>
</html>
