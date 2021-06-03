# Contador Visitas GitHub - Descripcion
Contador de visitas a tu pagina web, perfil de GitHub o repositorios. 

# Contador Visitas GitHub - Demo

<a href="https://github.com/KeyCuevasMelgarejo/KeyCuevasMelgarejo">
    <img alt="visitas" title="Visitas Perfil GitHub" src="https://github-contador-visitas.herokuapp.com/"/></a>

# Uso
### 1. Dale Fork a este repositorio
<a href="https://github.com/KeyCuevasMelgarejo/CONTADOR-VISITAS-GITHUB_/fork">
    <img alt="Folk" title="Fork Button" src="https://shields.io/badge/-DAR%20FORK-red.svg?&style=for-the-badge&logo=github&logoColor=white"/></a>

### 2. Crea tu base de datos
Puedes usar cualquier base de datos remota. Ingresa sus credenciales en el archivo conexion.php:
```bash
<?php
    $hostname_db = "hostname_db";
    $database_db = "database_db";
    $username_db = "username_db";
    $password_db = "password_db";
```
En el caso que no tengas una BD remota, puedes usar la que yo utilizo [RemoteMySql](https://remotemysql.com). Para crear tu BD alli, debes hacer lo siguiente:
```bash
# Create una cuenta
# Ingresa a tu cuenta
# Ve a la pestaña databases
# Dale clic a Create New Database (para que te aparezca el botón, primero debes contestar una pequeña encuesta).
# Te va a salir un div con un mensaje acerca de las credenciales de tu BD creada, ANÓTALA porque después desaparece.
# Ingresa las credenciales en el archivo conexion.php
```

### 3. Crea la tabla 'visitas' con los campos 'id' y 'github_contador_visitas' en tu BD remota
En el caso que uses [RemoteMySql](https://remotemysql.com), sigue los siguientes pasos:
```bash
# Ve a la pestaña databases,
# Da clic en ACTION y elige la opcion phpMyAdmin
# Usa las credenciales (user y password) de tu base de datos creada para ingresar a phpMyAdmin
# Dale clic en crear tabla 'visitas' con 2 columnas (id, github_contador_visitas)
```
Ya casi esta lista tu aplicación!

### 4. Despliega tu aplicación a heroku en 2 pasos

Dale click al siguiente botón y luego en la nueva pestaña que aparece dale 'Deploy App'

<a href="https://heroku.com/deploy?template=https://github.com/KeyCuevasMelgarejo/CONTADOR-VISITAS-GITHUB_/tree/master">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
<br />
<br />
Listo!

# Nota
Con las modificaciones necesarias al script (añadiendo nuevas columnas a la tabla 'visitas' en tu Base de datos, por ejemplo), puedes incluir visitas para uno o más repositorios.

## Participa
<p align="left">
  <a href="https://github.com/KeyCuevasMelgarejo/CONTADOR-VISITAS-GITHUB_/subscription">
    <img alt="Follow" title="Dale Me Gusta" src="https://shields.io/badge/-LIKE%20THIS%20REPO-informational.svg?&style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://github.com/KeyCuevasMelgarejo/CONTADOR-VISITAS-GITHUB_/issues/new">
    <img alt="Reportar problema" title="Ayudemos a mejorar" src="https://shields.io/badge/-REPORTA%20UN%20PROBLEMA-yellow.svg?&style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

