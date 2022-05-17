# AccesoItesi 
Sistema de acceso para el Instituto Tecnológico Superior de Irapuato Extensión Tarimoro

![Logo ISC](https://avatars.githubusercontent.com/u/83792380?s=400&u=282c0cb1ad15ed6222e0f09c08b6db7e80838324&v=4 "ISC")
###### ***@Copyright by ISC (Liz, Orla, Gina, Juan, Jesus, Karla)***
# ¿Quieres obtener el código fuente de una aplicación Android?
Por favor, visite https://codecanyon.net/item/attendance-with-qr-code-android-system-management/24718396


# Premio a la Innovación
! [nominado] (https://user-images.githubusercontent.com/11581453/53679420-937cb600-3d07-11e9-995d-cf60bd7a154e.gif)

Visita : https://www.phpclasses.org/package/10634-PHP-Manage-and-authenticate-company-employees-users.html

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


<img src="https://user-images.githubusercontent.com/11581453/74131411-367bc680-4c1f-11ea-8409-d9a8ea6bd5fb.png" width="200">  <img src="https://user-images.githubusercontent.com/11581453/74131417-38de2080-4c1f-11ea-9cb4-8cef333726b0.png" width="200">  <img src="https://user-images.githubusercontent.com/11581453/74131418-3a0f4d80-4c1f-11ea-9b08-76d69042cfe1.png" width="200">


# Nivel de usuario
- is_admin
- is_user (Su empleado o estudiante)
- is_subscriber

# Wiki
https://github.com/abedputra/Attendance-login-system/wiki

# inicio de sesión
- Pase : admin
- Usuario : admin@gmail.com

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
<b> (Necesita instalar Asistencia de empleados con QR en Google Play para asistir) https://play.google.com/store/apps/details?id=com.aandt.employeeattendancewithqr. El sistema de inicio de sesión de asistencia no puede funcionar sin la asistencia de los empleados con la aplicación QR< / b>
<br><br>
Esta aplicación no puede funcionar sin asistencia de empleados con QR, así que descárguela primero en Google Play.***
<br><br>

# Nueva versión
Versión Pro para la aplicación, por favor descargue desde aquí (https://play.google.com/store/apps/details?id=com.aandt.employeeattendancewithqrpro

# Migración de v1.0 a v2.0a
Actualice el archivo SQL. Por favor, siempre haga una copia de seguridad de sus datos primero.
<br>
A partir de v2.0a añadimos nueva tabla, para guardar el historial QR.


<br>
<br>
<br>

----------------------------------------------------------------------------------------------------------------------------------------

# -----Cómo usar esta aplicación?
Por favor, siga 2 pasos:<br>
1. Administración del sistema de configuración
Por favor, compruebe esto<br>
https://github.com/abedputra/Attendance-login-system/wiki/Settings-Management-System-%3F<br>
Por favor, consulte este video sobre cómo controlar el sistema
https://www.youtube.com/watch?v=s8pZl5UoT40

2. Settings Android Application<br>
Please check this<br>
https://github.com/abedputra/Attendance-login-system/wiki/Settings-on-Employee-Attendance-with-QR-Application-%3F

# -----How to get KEY?
-Go to Attendance login system link<br>
-Login<br>
-Go to settings<br>
-Click get Key<br>
-Save<br>
-Dont forget to add KEY to your application<br>

# -----How to get my employees data?
-Go to Attendance login system link<br>
-Login<br>
-Go to employee menu<br>

----------------------------------------------------------------------------------------------------------------------------------------

<br>
<br>
<br>

# Support me
Apóyame en <a href="https://www.patreon.com/abedputra">Patron</a>

# Acerca de
El sistema de inicio de sesión de asistencia se basa en el [codeigniter](https://github.com/bcit-ci/CodeIgniter). El sistema de inicio de sesión de asistencia se basa en el marco Bootstrap creado por [Mark Otto] (https://twitter.com/mdo) y [Jacob Thorton] (https://twitter.com/fat).
Hashing de contraseña con PBKDF2, Autor: [havoc AT defuse.ca](https://github.com/defuse).
Portado a CodeIgniter por [Richard Thornton](http://twitter.com/RichardThornton).
CodeIgniter Curl Libraries por [Philip Sturgeon](https://github.com/philsturgeon).

Si tiene alguna pregunta, envíeme un correo electrónico: abedputra@gmail.com
Visita: https://connectwithdev.com/page/blog/setup-employee-attendance-with-qr

# LICENCIA
La Licencia MIT (MIT).

Derechos de autor (c) 2017, Abed Putra.

Por favor, no dude en enviarme un correo electrónico si tiene algún problema.
Muchas gracias, mi correo electrónico: contact@abedputra.my.id.
