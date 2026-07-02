Para que el servicio funcione correctamente, el archivo db.json debe estar obligatoriamente en la raíz del proyecto (en el directorio principal del repositorio).
No debes meterlo dentro de ninguna carpeta especial.

📁 Estructura del repositorio en GitHub
La estructura limpia y correcta en tu cuenta de GitHub debe verse exactamente así:

nombre-repositorio/                     <- Nombre de tu repositorio
                  │
                  ├── db.json           <- ¡AQUÍ VA EL ARCHIVO! (En la raíz)
                  └── README.md         <- (Opcional) Instrucciones de la clase

Usa el código con precaución.

⚠️ Errores comunes que debes evitar:
Crear una carpeta llamada json/ o src/: 
   Si guardas el archivo como src/db.json, el servidor no lo va a encontrar y dará un error 404.
   Escribir el nombre en mayúsculas: El archivo se debe llamar estrictamente db.json en minúsculas.
   
🌐 Cómo se transformará en URL
Al colocarlo en la raíz, el sistema tomará de forma automática las "llaves" principales de tu archivo JSON y creará rutas separadas. 
