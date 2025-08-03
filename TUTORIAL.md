# Formación Estadísticas y Machine Learning - Alura

Este repositorio contiene los ejercicios, proyectos y archivos relacionados con la formación de Estadísticas y Machine Learning realizada en Alura LATAM.

---

## Cómo conectar esta carpeta a GitHub y subir el proyecto

### 1. Inicializar el repositorio local

```bash
git init
```
Inicializa un repositorio Git en la carpeta actual.

### 2. Configurar usuario (si no está configurado globalmente)
```bash
git config user.name "Tu Nombre"
git config user.email "tuemail@ejemplo.com"
```
Configura tu nombre y correo para los commits.

### 3. Agregar archivos y hacer primer commit
```bash
git add .
git commit -m "Primer commit: formación en estadística y machine learning"
```
Agrega todos los archivos y hace un commit con mensaje descriptivo.

### 4. Crear un repositorio en GitHub
Crear un repositorio nuevo en GitHub, por ejemplo:
formacion-estadisticas-ml-alura

### 5. Conectar el repositorio local con el remoto
```bash
git remote add origin https://github.com/tuusuario/formacion-estadisticas-ml-alura.git
```


Asocia tu repositorio local con el remoto en GitHub.

### 6. Ajustar la rama principal a main
```bash
git branch -M main
```
Renombra la rama actual a main para que coincida con la rama por defecto de GitHub.

### 7. Hacer push por primera vez
```bash
git push -u origin main
```
Sube tus commits al repositorio remoto.

## Solución a error común al hacer push
Si recibes un error como este:

```pgsql
error: failed to push some refs to 'https://github.com/...'
Updates were rejected because the remote contains work that you do not have locally.
```
Significa que el repositorio remoto tiene commits que tu copia local no tiene (por ejemplo, un README creado desde la web de GitHub).

Para solucionarlo:

### 1. Hacer pull con historial no relacionado
```bash
git pull origin main --allow-unrelated-histories
```
Esto descarga y combina el trabajo remoto con tu trabajo local.

### 2. Confirmar el merge
Git abrirá un editor con un mensaje para el commit del merge.

Guarda y cierra ese archivo para continuar.

### 3. Subir los cambios combinados
```bash
git push -u origin main
```
### Notas adicionales
Para ver en qué rama estás, puedes usar:

```bash
git branch
```

Siempre es buena idea escribir mensajes claros en tus commits para mantener el historial entendible.

¡Listo! Ahora tu carpeta está correctamente versionada y sincronizada con GitHub.

Contacto
Para dudas o ayuda, puedes contactarme en ferpaye@gmail.com.

---