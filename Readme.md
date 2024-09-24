# OBJETIVO LABORATORIO DE GIT #
---
1. __CREA UN REPOSITORIO LOCAL__ 
   
  - Abre tu terminal y navega hasta el directorio donde deseas crear el repositorio
  
 ![alt text](<markdown fotos/captura.png>)

  - Crea una carpeta con el nombre del repositorio.
  
  ![alt text](<markdown fotos/Captura de pantalla 2024-09-04 a las 10.17.28.png>)

  - Ingresa a la carpeta que acabas de crear.
  
![alt text](<markdown fotos/Captura de pantalla 2024-09-05 a las 11.25.11.png>)

  - Inicializa el repositorio de Git.
  
  ![alt text](<markdown fotos/Captura de pantalla 2024-09-04 a las 10.18.41.png>)

2. __SUBIR EL REPOSITORIO A GITHUB__
   
  -  Crea un nuevo repositorio en GitHub.
  
  ![alt text](<markdown fotos/Captura de pantalla 2024-09-04 a las 10.20.33.png>)

 - Copia el URL del repositorio que acabas de crear en GitHub
  
  ![alt text](<markdown fotos/Captura de pantalla 2024-09-05 a las 11.33.46.png>)

 - Conecta tu repositorio local con el repositorio en GitHub.
  
![alt text](<markdown fotos/Git remote add origin .png>)
  
 - Verifica que la conexión se haya establecido correctamente.

![alt text](<markdown fotos/Captura de pantalla 2024-09-04 a las 9.44.36.png>)

3. __Hacer un commit y un push__
  - Crea un archivo en la carpeta del repositorio.
  
![alt text](<markdown fotos/touch git ignore.png>)

 - Añade el archivo al staging.

![alt text](<markdown fotos/git add .gitignore.png>)

 - Crea un commit con un mensaje descriptivo.

![alt text](<markdown fotos/Git commit se añade el git ignore.png>)

 - Sube los cambios al repositorio en GitHub.
  
![alt text](<markdown fotos/git push origin.png>)

![alt text](<markdown fotos/cambios subidos a github.png>)

4. __Crear una rama__
   
  - Crea una rama nueva llamada "development".
 
  ![alt text](<markdown fotos/Captura de pantalla 2024-09-23 a las 11.47.48.png>)

 - Cambia a la nueva rama.

![alt text](<markdown fotos/Captura de pantalla 2024-09-23 a las 11.51.07.png>)

 - Realiza algunos cambios en el archivo que creaste.

![alt text](<markdown fotos/Captura de pantalla 2024-09-23 a las 12.04.30.png>)

 - Añade y haz un commit con los cambios en la rama "development".

![alt text](<markdown fotos/Captura de pantalla 2024-09-23 a las 12.06.59.png>)

 - Sube los cambios a Github.
  
![alt text](<Captura de pantalla 2024-09-23 a las 12.09.53.png>)

5. __Hacer un merge__
   
 - Vuelve a la rama "main".
  
![alt text](<markdown fotos/Captura de pantalla 2024-09-23 a las 12.12.17.png>)

 - Haz un merge de la rama "development" a la rama "main".


 - Si no hay conflictos, los cambios realizados en la rama "development" se incorporarán a la rama "main".



- Haz un push de los cambios al repositorio en GitHub.
