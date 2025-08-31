# Pasos a seguir para subir un proyecto a Git.

1. Crea un repositorio en GitHub
Ve a GitHub y crea una cuenta si no tienes una. 
Crea un nuevo repositorio haciendo clic en el botón "New" o "Más" y luego en "New repository". 
Dale un nombre, una descripción y elige la visibilidad (público o privado). 
No marques la opción de inicializar con un README en este paso para poder subir tu proyecto desde cero. 
Haz clic en "Create repository". 
Copia la URL del repositorio (terminada en .git) que te proporciona GitHub.

2. Inicializa y configura tu proyecto localmente
Abre tu terminal o Git Bash y navega hasta la carpeta raíz de tu proyecto usando el comando cd. 
Ejecuta git init para inicializar el repositorio Git en tu carpeta local. 

3. Añade y confirma tus archivos
Añade todos los archivos del proyecto al área de preparación con git add .
Confirma estos cambios con un mensaje descriptivo usando git commit -m "Tu mensaje aquí". Por ejemplo: git commit -m "Primer commit de los archivos del proyecto". 

4. Conecta tu repositorio local al remoto 
Enlaza tu repositorio local con el repositorio remoto de GitHub usando el comando git remote add origin <URL>. Asegúrate de reemplazar <URL> por la URL que copiaste en el paso 1.

5. Sube tu proyecto a GitHub 
Finalmente, envía tus archivos al repositorio remoto con el comando git push -u origin main. Si tu rama principal se llama diferente (por ejemplo, master), reemplaza main por el nombre de tu rama.

//Crear un archivo GIt ignore y añadir en él la carpeta reto_" y todas las imagenes.
al Hacerlo y subir de nuevo el proyecto, se han subidos todos los archivos excepto lo que metimos dentro de este archivo .gitignore.