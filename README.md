# AccesoItesi 
Sistema de acceso para el Instituto Tecnológico Superior de Irapuato Extensión Tarimoro

![Logo ISC](https://avatars.githubusercontent.com/u/83792380?s=400&u=282c0cb1ad15ed6222e0f09c08b6db7e80838324&v=4 "ISC")
###### ***@Copyright by ISC (Liz, Orlando, Gina, Juan, Jesus, Karla)***


# Característica
- Agregar usuario
- Eliminar usuario
- Prohibir, anular la prohibición del usuario
- Registrar nuevo usuario enviado al token de correo electrónico
- Olvidar contraseña
- Nivel de usuario de rol
- Editar perfil de usuario
- Perfil de usuario de Gravatar
- Recaptcha por Google
- Lista de asistencia de los empleados
- Exportar la asistencia de los empleados a CSV o XLS
- Verifique la asistencia de sus empleados tarde o a tiempo todos los días
- Revise la asistencia de sus empleados durante 1 semana, 1 mes, 1 año, etc.
- Genere QR para el nombre de su empleado

! [código qr de asistencia del sistema] (https://user-images.githubusercontent.com/11581453/74131506-64f9a180-4c1f-11ea-8aea-b4847f02d0ec.png)

<img src="https://i.pinimg.com/564x/7c/13/79/7c137967d7b208825ce967a89c49e4c6.jpg" width="180" height="350"> 
<img src="https://cdn.pixabay.com/photo/2022/05/18/04/12/04-12-11-33_960_720.jpg" width="180" height="350"> 
<img src="https://cdn.pixabay.com/photo/2022/05/18/04/12/04-12-17-462_960_720.jpg" width="180" height="350">


# Nivel de usuario
- Administrador
- Docente
- Alumno


# inicio de sesión
- Contraseña : pablo1234
- Usuario : pabloperezm988@gmail.com

# Comprobar nivel de usuario
controlador.php
```
comprobar el nivel de usuario
if(empty($data['rol'])){
 redirect(site_url().» main/login/');
}
$dataLevel = $this->userlevel->checkLevel($data['role']);
comprobar el nivel de usuario
if($dataLevel == "is_admin"){
 (su código aquí)
}
```
# Advertencia
<b> (Necesita instalar Asistencia de empleados con QR) https://drive.google.com/file/d/11JviitF0zvedO3XNnMDLLFu3kkfBuYdY/view. El sistema de inicio de sesión de asistencia no puede funcionar sin la asistencia de los empleados con la aplicación QR< / b>
<br><br>
Esta aplicación no puede funcionar sin asistencia de empleados con QR, así que descárguela primero en drive***
<br><br>


<br>
<br>
<br>

----------------------------------------------------------------------------------------------------------------------------------------

# -----Cómo usar esta aplicación?
Por favor, siga 2 pasos:<br>
1. Administración del sistema de configuración
Por favor, compruebe esto<br>
https://github.com/JesusGGomezR/AccesoItesi/wiki#descargar-o-clonar-primero<br>

2. Configuracion para aplicacion Android <br>
Por favor revise this<br>
https://github.com/abedputra/Attendance-login-system/wiki/Settings-on-Employee-Attendance-with-QR-Application-%3F

# ----Cómo obtener la CLAVE?
-Ir al enlace del sistema de inicio de sesión de Asistencia<br>
-Iniciar sesión<br>
-Ir a configuración<br>
-Haga clic en obtener clave<br>
-Guardar<br>
-No olvide agregar CLAVE a su aplicación<br>

# -----¿Cómo obtener los datos de mis empleados?
-Ir al enlace del sistema de inicio de sesión de Asistencia<br>
-Iniciar sesión<br>
-Ir al menú de empleados<br>

----------------------------------------------------------------------------------------------------------------------------------------

<br>
<br>
<br>

# Acerca de
El sistema de inicio de sesión de asistencia se basa en el [codeigniter](https://github.com/bcit-ci/CodeIgniter). El sistema de inicio de sesión de asistencia se basa en el marco Bootstrap creado por [Mark Otto] (https://twitter.com/mdo) y [Jacob Thorton] (https://twitter.com/fat).

Si tiene alguna pregunta, envíeme un correo electrónico: jssbrrgn@gmail.com, omn76231@gmail.com, karla29.vazquezl@gmailcom, pabloperezm988@gmail.com, georginaalc4010@gmail.com y karen.alvareza2010@gmail.com



###### ***@Copyright by ISC (Liz, Orla, Gina, Juan, Jesus, Karla)***

Por favor, no dude en enviarme un correo electrónico si tiene algún problema.
Muchas gracias, mi correo electrónico: jssbrrgn@gmail.com, omn76231@gmail.com, karla29.vazquezl@gmail.com, pabloperezm988@gmail.com, georginaalc4010@gmail.com y karen.alvareza2010@gmail.com
