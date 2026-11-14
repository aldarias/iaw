# EXAMEN DE IMPLANTACIÓN DE APLICACIONES WEB (IAW) - 1ª EVALUACIÓN
## MODELO 1

**Módulo Profesional:** Implantación de Aplicaciones Web (IAW) — 2º ASIR  
**Curso Académico:** 2026-2027 | **Centro:** CEEDCV  
**Profesor:** Paco Aldarias  
**Duración:** 1 hora y 30 minutos (90 minutos)  
**Calificación Total:** 10 puntos (Nota Final = Media Aritmética de RA1 y RA3)

---

### DATOS DEL ALUMNO/A
- **Nombre y Apellidos:** __________________________________________________________________
- **Fecha del Examen:** ________________________________________

---

### I. INSTRUCCIONES GENERALES Y CRITERIOS DE CALIFICACIÓN

1. **Normas de Permanencia y Firma de Asistencia:**
   - **Tiempo mínimo de permanencia:** No se podrá entregar el examen ni abandonar el aula hasta pasados **15 minutos** desde el inicio de la prueba.
   - **Firma obligatoria de asistencia:** Al entregar la prueba, el alumno/a **deberá firmar obligatoriamente la hoja de registro de asistencia** antes de salir del aula.

2. **Resultados de Aprendizaje (RA) Evaluados:**
   En este examen de 1ª Evaluación se evalúan **exclusivamente el RA1 y el RA3**:
   - **RA1: Prepara el entorno de desarrollo y los servidores de aplicaciones Web instalando e integrando las funcionalidades necesarias.**
     - *Abarca:* **UD1** (Tecnologías web, protocolos HTTP/HTTPS, arquitectura cliente-servidor, puertos, URL, Git y GitHub) y **UD2** (Servidores web Apache/Nginx y SGBD MySQL/MariaDB).
   - **RA3: Administra gestores de contenidos adaptándolos a los requerimientos y garantizando la integridad de la información.**
     - *Abarca:* **UD4** (Administración de usuarios y roles en CMS, organización mediante categorías y etiquetas, seguridad 2FA y copias de seguridad regla 3-2-1).

3. **Estructura de la Prueba y Evaluación por RA:**
   - Cada Resultado de Aprendizaje (**RA1** y **RA3**) se valora de **0 a 10 puntos**.
   - **Nota Final del Examen:** Es la media aritmética simple entre la nota de RA1 y RA3:
     $$\text{Nota Final} = \frac{\text{Nota RA1} + \text{Nota RA3}}{2}$$
   - **Parte 1: Bloque Tipo Test (5,0 Puntos globales):** 20 preguntas con 4 opciones (1 cierta, 3 falsas). Respuesta correcta: **+0,25 ptos**. Respuesta incorrecta: **-0,0625 ptos** (4 mal restan 1 bien).
   - **Parte 2: Bloque de Desarrollo Corto (5,0 Puntos globales):** 5 preguntas de respuesta escrita corta (1,0 pto por pregunta).

---

## PARTE 1: BLOQUE TIPO TEST (20 PREGUNTAS - TOTAL: 5,0 PUNTOS)

---

### SECCIÓN 1.1: PREGUNTAS TIPO TEST DE RA1 (Preguntas 1 a 10)

#### Pregunta 1 [RA1]
En la arquitectura cliente-servidor de aplicaciones web, ¿cuál es el puerto estándar y bien conocido por defecto que utiliza el protocolo seguro HTTPS para transmitir información cifrada mediante SSL/TLS?
- **A)** Puerto 21
- **B)** Puerto 80
- **C)** Puerto 443
- **D)** Puerto 8080

#### Pregunta 2 [RA1]
¿Qué método de petición HTTP se caracteriza por enviar los datos del formulario integrados explícitamente en la propia URL de la solicitud, siendo visibles para el usuario y quedando registrados en el historial del navegador?
- **A)** Método POST
- **B)** Método GET
- **C)** Método PUT
- **D)** Método DELETE

#### Pregunta 3 [RA1]
Dentro de la clasificación de servidores web según la infraestructura hardware/alojamiento, ¿qué modalidad proporciona un entorno virtualizado con recursos dinámicos y escalables que simula el funcionamiento de una máquina dedicada a un coste más reducido?
- **A)** Servidor Compartido (Web Hosting)
- **B)** Servidor Dedicado Físico
- **C)** Servidor Virtual Privado (VPS)
- **D)** Servidor NAS de red local

#### Pregunta 4 [RA1]
¿Qué componentes forman la arquitectura clásica de la pila de software (Software Stack) conocida como LAMP?
- **A)** Linux, Apache, MySQL/MariaDB y PHP
- **B)** Linux, Nginx, PostgreSQL y Python
- **C)** Windows, Apache, MariaDB y Perl
- **D)** Linux, Tomcat, SQLite y PHP

#### Pregunta 5 [RA1]
Tras instalar Git en un sistema operativo, ¿qué comando de terminal debe ejecutarse para configurar globalmente el nombre del desarrollador que firmará los commits en el sistema?
- **A)** `git set user.name "Nombre"`
- **B)** `git config --global user.name "Nombre"`
- **C)** `git init --user "Nombre"`
- **D)** `git commit --user "Nombre"`

#### Pregunta 6 [RA1]
En el flujo de trabajo básico con el sistema de control de versiones Git, ¿cuál es el comando que traslada los archivos modificados desde el directorio de trabajo a la zona de intercambio temporal (Staging Area o Área de Preparación)?
- **A)** `git commit`
- **B)** `git push`
- **C)** `git add`
- **D)** `git checkout`

#### Pregunta 7 [RA1]
Si en un repositorio Git ejecutas la orden `git reset --hard HEAD~1`, ¿cuál es el resultado exacto en el estado del repositorio?
- **A)** Se deshace el último commit pero se conservan los cambios tanto en la zona de staging como en el directorio de trabajo.
- **B)** Permite modificar únicamente el mensaje del último commit realizado.
- **C)** Se deshace el último commit y se eliminan de forma irreversible todas las modificaciones en el directorio de trabajo y el área de staging.
- **D)** Se crea una rama alternativa manteniendo intacto el historial de la rama actual.

#### Pregunta 8 [RA1]
¿Qué comando de Git permite crear una nueva rama denominada `funcionalidad-login` y posicionarse inmediatamente en ella dentro del entorno de trabajo?
- **A)** `git branch funcionalidad-login --switch`
- **B)** `git checkout -b funcionalidad-login`
- **C)** `git merge -b funcionalidad-login`
- **D)** `git init branch funcionalidad-login`

#### Pregunta 9 [RA1]
En la plataforma GitHub, ¿cómo se denomina la solicitud formal que envía un desarrollador al propietario de un repositorio original para proponer la integración de los cambios realizados en su copia bifurcada (fork)?
- **A)** Merge Request local
- **B)** Commit Push
- **C)** Pull Request (PR)
- **D)** Fork Synchronization

#### Pregunta 10 [RA1]
En un servidor web Apache instalado sobre Ubuntu Server, tras crear el archivo de host virtual `/etc/apache2/sites-available/mi_tienda.conf`, ¿qué comando de la suite de Apache se utiliza para activar dicho sitio web?
- **A)** `sudo a2enmod mi_tienda.conf`
- **B)** `sudo a2ensite mi_tienda.conf`
- **C)** `sudo systemctl enable mi_tienda.conf`
- **D)** `sudo apache2ctl enable mi_tienda.conf`

---

### SECCIÓN 1.2: PREGUNTAS TIPO TEST DE RA3 (Preguntas 11 a 20)

#### Pregunta 11 [RA3]
En una instalación estándar de WordPress en servidor propio, ¿en qué archivo PHP clave se almacenan las constantes de configuración con los datos de acceso a la base de datos MySQL (DB_NAME, DB_USER, DB_PASSWORD, DB_HOST)?
- **A)** `config.xml`
- **B)** `wp-config.php`
- **C)** `.htaccess`
- **D)** `settings.json`

#### Pregunta 12 [RA3]
En la administración de usuarios y roles predefinidos de WordPress, ¿qué perfil permite a un usuario redactar y modificar sus propias entradas pero le impide publicarlas directamente, requiriendo la revisión y aprobación de un Editor o Administrador?
- **A)** Suscriptor
- **B)** Colaborador
- **C)** Autor
- **D)** Editor

#### Pregunta 13 [RA3]
¿Cuál es la diferencia fundamental en la taxonomía de contenidos de un CMS entre Categorías y Etiquetas?
- **A)** Las categorías son no jerárquicas y las etiquetas admiten subetiquetas jerárquicas.
- **B)** Las categorías son jerárquicas (admiten subcategorías) para organizar grandes secciones temáticas, mientras que las etiquetas no son jerárquicas y definen conceptos específicos.
- **C)** Las etiquetas son obligatorias para publicar y las categorías son de uso exclusivo para administradores.
- **D)** No existe ninguna diferencia funcional; son dos nombres para la misma herramienta.

#### Pregunta 14 [RA3]
En la gestión de copias de seguridad de aplicaciones web, ¿qué establece la regla de buenas prácticas 3-2-1?
- **A)** Mantener 3 backups en el mismo servidor, en 2 carpetas distintas y 1 en la papelera de reciclaje.
- **B)** Guardar al menos 3 copias de los datos, en 2 soportes o medios diferentes, y conservar al menos 1 copia fuera de las instalaciones (en la nube o ubicación remota).
- **C)** Realizar 3 copias diarias durante 2 semanas y conservarlas durante 1 mes.
- **D)** Emplear 3 plugins distintos para respaldar 2 bases de datos en 1 solo sitio.

#### Pregunta 15 [RA3]
¿Qué mecanismo de seguridad reforzado implementa un CMS para exigir que el usuario introduzca un código temporal generado en su dispositivo móvil además de su contraseña al iniciar sesión?
- **A)** Protocolo HTTP estático
- **B)** Autenticación de Dos Factores (2FA)
- **C)** Módulo mod_rewrite de Apache
- **D)** Control de acceso por archivo .htaccess

#### Pregunta 16 [RA3]
En la administración del sistema de archivos de WordPress, ¿qué permisos octales POSIX se recomiendan establecer por seguridad para los directorios (como `wp-content`) y para los archivos planos respectivamente?
- **A)** 777 para directorios y 777 para archivos
- **B)** 755 para directorios y 644 para archivos
- **C)** 600 para directorios y 700 para archivos
- **D)** 444 para directorios y 755 para archivos

#### Pregunta 17 [RA3]
¿Qué capacidad diferenciadora posee un usuario con el rol de Editor en WordPress frente a un usuario con el rol de Autor?
- **A)** El Editor puede editar, publicar y eliminar entradas creadas por cualquier otro usuario del CMS.
- **B)** El Editor puede instalar plugins y modificar el tema visual del sitio.
- **C)** El Editor puede modificar el archivo `wp-config.php` desde el panel de administración.
- **D)** El Editor es el único rol que puede crear usuarios en el sistema.

#### Pregunta 18 [RA3]
Para garantizar la posibilidad de una restauración completa y funcional de un gestor de contenidos CMS tras un fallo catastrófico, ¿cuáles son los dos elementos esenciales que deben respaldarse obligatoriamente?
- **A)** El historial de navegación del servidor y las imágenes en caché.
- **B)** La base de datos relacional (MySQL) y los archivos de la aplicación (núcleo, temas, plugins y subidas).
- **C)** Los registros de acceso (access.log) y el archivo de contraseñas `/etc/shadow`.
- **D)** Únicamente el archivo `index.php` de la raíz web.

#### Pregunta 19 [RA3]
¿Qué función principal cumplen los Registros de Actividad (Audit Logs) en la administración de un CMS multiusuario?
- **A)** Aumentar la velocidad de carga de las imágenes del sitio.
- **B)** Registrar eventos y acciones de usuarios (inicios de sesión, cambios en contenidos o configuraciones) para permitir la auditoría de seguridad y trazabilidad.
- **C)** Generar automáticamente copias de seguridad de la base de datos en tiempo real.
- **D)** Traducir automáticamente los contenidos del CMS a varios idiomas.

#### Pregunta 20 [RA3]
¿Qué constante de configuración de PHP introducida en `wp-config.php` permite deshabilitar el editor integrado de temas y plugins desde la interfaz de administración para prevenir la inyección de código malicioso?
- **A)** `define('ALLOW_UNFILTERED_UPLOADS', true);`
- **B)** `define('DISALLOW_FILE_EDIT', true);`
- **C)** `define('WP_DEBUG', true);`
- **D)** `define('AUTOMATIC_UPDATER_DISABLED', true);`

---

### HOJA DE RESPUESTAS - PARTE 1 (TIPO TEST)

> **Instrucciones de rellenado:** Anote la letra de la opción seleccionada (A, B, C o D) en la casilla correspondiente a cada pregunta (del 1 al 20).

| Pregunta | Respuesta |
| :---: | :---: |
| **1** | |
| **2** | |
| **3** | |
| **4** | |
| **5** | |
| **6** | |
| **7** | |
| **8** | |
| **9** | |
| **10** | |
| **11** | |
| **12** | |
| **13** | |
| **14** | |
| **15** | |
| **16** | |
| **17** | |
| **18** | |
| **19** | |
| **20** | |

---

## PARTE 2: BLOQUE DE PREGUNTAS CORTAS DE DESARROLLO (5 PREGUNTAS - TOTAL: 5,0 PUNTOS)

---

### SECCIÓN 2.1: PREGUNTAS DE DESARROLLO DE RA1

#### Pregunta 1 (1,0 Punto) [RA1] — Control de Versiones (Git)
Imagina que estás trabajando en la rama principal `main` de un repositorio Git. Se te pide implementar una nueva funcionalidad llamada `sistema-usuarios`.
1. Indique la secuencia exacta de comandos Git para **crear la rama `sistema-usuarios` y cambiar a ella**.
2. Una vez realizados y confirmados (commit) los cambios en la rama `sistema-usuarios`, detalle los comandos necesarios para **volver a la rama `main` y fusionar (merge) los cambios** de la nueva rama.
3. Si durante la fusión surge un conflicto en el archivo `config.php`, explique brevemente **qué pasos y comandos debe seguir para resolver el conflicto** de forma correcta.

#### Pregunta 2 (1,0 Punto) [RA1] — Servidores Web (Apache Host Virtual)
Se requiere desplegar el sitio web de una tienda en línea en un servidor Ubuntu Server con Apache2. El directorio raíz de los archivos web estará ubicado en `/var/www/html/tienda`.
1. Escriba los comandos de terminal necesarios para **crear dicho directorio y asignar los permisos de propiedad** al usuario y grupo del servidor web (`www-data`).
2. Muestre la estructura básica del archivo de configuración del Host Virtual (`/etc/apache2/sites-available/tienda.conf`), indicando las directivas necesarias para escuchar en el puerto 80, definir el nombre del servidor (`ServerName tienda.local`) y la raíz del documento (`DocumentRoot`).
3. Indique el comando para **activar el sitio virtual** en Apache y el comando para **recargar la configuración del servicio** `apache2`.

#### Pregunta 3 (1,0 Punto) [RA1] — Servidores de Bases de Datos (MySQL)
Para proceder a la instalación de un CMS WordPress, es necesario preparar manualmente la base de datos y su usuario correspondiente en el servidor MySQL desde la línea de comandos (`mysql -u root -p`).
Escriba la secuencia exacta de sentencias SQL necesarias para realizar las siguientes operaciones:
1. Crear una base de datos llamada `bd_wordpress` configurada con el juego de caracteres `utf8mb4` y el cotejamiento `utf8mb4_unicode_ci`.
2. Crear un usuario de base de datos llamado `wp_user` asociado únicamente a `localhost` con la contraseña `'ClaveSegura2026!'`.
3. Otorgar **todos los privilegios** al usuario `wp_user` sobre **todas las tablas de la base de datos `bd_wordpress`**, aplicar los cambios en la tabla de privilegios (`FLUSH PRIVILEGES`) y salir de la consola MySQL.

---

### SECCIÓN 2.2: PREGUNTAS DE DESARROLLO DE RA3

#### Pregunta 4 (1,0 Punto) [RA3] — Administración de CMS (Usuarios y Roles)
En la administración de un gestor de contenidos como WordPress, la asignación correcta de roles de usuario es vital para la seguridad y la organización del trabajo colaborativo.
1. Compare y explique detalladamente la diferencia de privilegios entre el rol de **Editor**, el rol de **Autor** y el rol de **Colaborador**.
2. Justifique por qué un usuario con rol de **Colaborador** no puede publicar directamente sus artículos en el sitio web y detalle qué perfil de usuario debe intervenir para autorizar o publicar dicha entrada.

#### Pregunta 5 (1,0 Punto) [RA3] — Seguridad y Copias de Seguridad en CMS
El mantenimiento operativo de un CMS requiere una política estricta de respaldos y recuperación ante desastres.
1. Indique cuáles son los **dos componentes indispensables** que forman parte de la arquitectura de una aplicación web CMS y que se deben respaldar obligatoriamente para garantizar la restauración completa del sitio.
2. Explique brevemente cómo se realiza la copia de seguridad de cada uno de esos dos componentes en un entorno Linux/WordPress (mencionando herramientas de comandos como `mysqldump` o `tar` y plugins de CMS).
3. Justifique la aplicación de la **regla 3-2-1** en el almacenamiento de dichas copias de seguridad.

---

## ANEXO PARA EL PROFESORADO: SOLUCIONARIO Y CRITERIOS DE CORRECCIÓN (MODELO 1)

### 1. Solucionario de la Parte Tipo Test (Modelo 1)

| Pregunta | RA | Respuesta | Justificación Teórica |
| :---: | :---: | :---: | :--- |
| **Q1** | RA1 | **C** | HTTPS opera por defecto en el puerto seguro 443 con cifrado SSL/TLS. |
| **Q2** | RA1 | **B** | El método GET adjunta los parámetros en la URL, haciéndolos visibles en el navegador. |
| **Q3** | RA1 | **C** | Un VPS simula un servidor dedicado en un entorno virtualizado a menor coste. |
| **Q4** | RA1 | **A** | La pila LAMP está formada por Linux, Apache, MySQL/MariaDB y PHP. |
| **Q5** | RA1 | **B** | `git config --global user.name` establece la identidad global del autor de los commits. |
| **Q6** | RA1 | **C** | `git add` traslada cambios al Staging Area (Índice). |
| **Q7** | RA1 | **C** | `git reset --hard HEAD~1` deshace el commit y destruye los cambios del área de trabajo. |
| **Q8** | RA1 | **B** | `git checkout -b <rama>` crea y conmuta a la nueva rama. |
| **Q9** | RA1 | **C** | Un Pull Request solicita la fusión de un fork en el repositorio base. |
| **Q10** | RA1 | **B** | `a2ensite` activa un archivo de configuración de host virtual en Apache. |
| **Q11** | RA3 | **B** | `wp-config.php` contiene las credenciales de la base de datos MySQL en WordPress. |
| **Q12** | RA3 | **B** | El Colaborador puede escribir borradores pero no puede publicarlos directamente. |
| **Q13** | RA3 | **B** | Las categorías son jerárquicas; las etiquetas son planas y específicas. |
| **Q14** | RA3 | **B** | Regla 3-2-1: 3 copias, 2 soportes distintos, 1 fuera de la ubicación (nube). |
| **Q15** | RA3 | **B** | 2FA añade una segunda verificación con código temporal en el móvil. |
| **Q16** | RA3 | **B** | Permisos recomendados en WordPress: 755 para directorios y 644 para archivos. |
| **Q17** | RA3 | **A** | El Editor gestiona, edita y publica las entradas de todos los usuarios del CMS. |
| **Q18** | RA3 | **B** | Es imprescindible respaldar la BD MySQL y los archivos de la aplicación. |
| **Q19** | RA3 | **B** | Los audit logs permiten la trazabilidad y auditoría de eventos de usuarios. |
| **Q20** | RA3 | **B** | `DISALLOW_FILE_EDIT` inhabilita la edición de código desde el panel de WordPress. |

---

### 2. Solucionario y Rúbrica de Desarrollo (Modelo 1)

#### Pregunta 1 (Git — Ramas y Conflictos) [RA1] (1,0 Punto)
- **1. Creación y cambio de rama (0,3 ptos):** `git checkout -b sistema-usuarios` (o `git branch` + `git checkout`).
- **2. Fusión en main (0,3 ptos):** `git checkout main` seguido de `git merge sistema-usuarios`.
- **3. Resolución de conflicto (0,4 ptos):** Identificar marcas `<<<<<<<` / `>>>>>>>`, editar el archivo borrando marcas, guardar, ejecutar `git add config.php` y hacer `git commit -m "Resuelto conflicto"`.

#### Pregunta 2 (Apache — Host Virtual) [RA1] (1,0 Punto)
- **1. Directorio y permisos (0,3 ptos):** `sudo mkdir -p /var/www/html/tienda` y `sudo chown -R www-data:www-data /var/www/html/tienda`.
- **2. Configuración Host Virtual (0,4 ptos):** Bloque `<VirtualHost *:80>` con `ServerName tienda.local` y `DocumentRoot /var/www/html/tienda`.
- **3. Activación y recarga (0,3 ptos):** `sudo a2ensite tienda.conf` y `sudo systemctl reload apache2`.

#### Pregunta 3 (MySQL — Base de Datos y Usuario) [RA1] (1,0 Punto)
```sql
CREATE DATABASE bd_wordpress DEFAULT CHARACTER 
SET utf8mb4 COLLATE utf8mb4_unicode_ci; -- (0,3 ptos)

CREATE USER 'wp_user'@'localhost' 
IDENTIFIED BY 'ClaveSegura2026!'; -- (0,3 ptos)

GRANT ALL PRIVILEGES ON bd_wordpress.* TO 'wp_user'@'localhost'; 
FLUSH PRIVILEGES; EXIT; -- (0,4 ptos)
```

#### Pregunta 4 (CMS — Roles y Permisos) [RA3] (1,0 Punto)
- **1. Comparación de roles (0,5 ptos):**
  - **Editor:** Control total sobre contenidos de cualquier usuario (publica, edita, elimina).
  - **Autor:** Publica y edita sus propias entradas únicamente.
  - **Colaborador:** Escribe borradores propios pero no sube multimedia ni publica.
- **2. Justificación (0,5 ptos):** El rol Colaborador evita publicaciones no supervisadas. Requiere la aprobación y publicación final por parte de un **Editor** o **Administrador**.

#### Pregunta 5 (CMS — Seguridad y Copias de Seguridad) [RA3] (1,0 Punto)
- **1. Componentes (0,3 ptos):** Archivos web (`wp-content`, `wp-config.php`) y la Base de Datos MySQL.
- **2. Herramientas de copia (0,4 ptos):** `mysqldump` / plugin UpdraftPlus para la BD y `tar -czvf` / FTP para archivos.
- **3. Regla 3-2-1 (0,3 ptos):** 3 copias totales, en 2 medios distintos y 1 almacenamiento remoto/nube para prevenir pérdidas catastróficas.
