# Curso-de-html-basico
Un pequeño proyecto para poner en práctica lo que hemos aprendido del curso



## 🟢 Paso 1: Preparar tu proyecto
- Abre **Visual Studio Code**.  
- Crea una carpeta para tu proyecto (ejemplo: `CursoHTML`).  
- Dentro, guarda tus archivos `.html` y `.css`.

---

## 🔑 Paso 2: Inicializar Git
En la terminal integrada de VS Code escribe:
```bash
git init
```
👉 Esto convierte tu carpeta en un repositorio local.

---

## 📂 Paso 3: Crear el repositorio en GitHub
1. Ve a [GitHub](https://github.com).  
2. Haz clic en **New repository**.  
3. Ponle un nombre (ejemplo: `Curso-de-html-basico`).  
4. Decide si será público o privado.  
5. Crea el repositorio.  

---

## 🔗 Paso 4: Conectar tu proyecto local con GitHub
Copia la URL del repositorio (ejemplo: `https://github.com/usuario/Curso-de-html-basico.git`).  
En VS Code escribe:
```bash
git remote add origin https://github.com/usuario/Curso-de-html-basico.git
```

---

## 📝 Paso 5: Guardar tus archivos en Git
1. **Agregar todos los archivos**:
   ```bash
   git add .
   ```
2. **Crear tu primer commit**:
   ```bash
   git commit -m "Primer commit: proyecto HTML básico"
   ```

---

## 📤 Paso 6: Subir a GitHub
```bash
git branch -M main
git push -u origin main
```
👉 Esto envía tu proyecto a la rama principal (`main`) en GitHub.

---

## ✅ Paso 7: Verificar
- Ve a tu repositorio en GitHub.  
- Actualiza la página.  
- ¡Tus archivos ya estarán ahí listos para compartir con tu compañera! 🎉

---

💡 Consejo: Cada vez que hagas cambios, repite solo estos tres pasos:  
```bash
git add .
git commit -m "Descripción de lo que cambiaste"
git push origin main
```




## 📂 1. Clonar el repositorio
se debe abrir la terminal (puede ser la de **Visual Studio Code**) y ejecutar:

```bash
git clone https://github.com/gamler2/Curso-de-html-basico.git
```

👉 Esto descargará todo el proyecto en una carpeta local llamada `Curso-de-html-basico`.

---

## 🔄 2. Entrar a la carpeta
Después de clonar, debe entrar a la carpeta del proyecto:

```bash
cd Curso-de-html-basico
```

---

## 📌 3. Revisar la rama principal
Normalmente la rama principal se llama `main`. Para asegurarse:

```bash
git branch -a
```

Si está en otra rama, puede cambiarse con:
```bash
git checkout main
```

---

## 🔧 4. Mantenerse sincronizada
Cada vez que quiera traer tus cambios más recientes, debe usar:

```bash
git pull origin main
```

👉 Esto actualiza su copia local con lo que tú hayas subido.

---

## 🛠️ 5. Flujo colaborativo
- **Tú subes cambios** con `git add .`, `git commit -m "mensaje"`, `git push origin main`.  
- **Ella los descarga** con `git pull origin main`.  
- Si ella también hace cambios, debe subirlos con `git push origin main`.  

---


## 🔄 Flujo básico para guardar cambios en GitHub

1. **Verifica qué cambió**  
   En la terminal de VS Code escribe:
   ```bash
   git status
   ```
   👉 Te mostrará los archivos modificados.

2. **Agrega los archivos al área de preparación**  
   Si quieres subir todos los cambios:
   ```bash
   git add .
   ```
   (El punto significa “todos los archivos modificados”).

3. **Crea un commit con mensaje descriptivo**  
   ```bash
   git commit -m "Agregué sección de hobbies en la página Sobre mí"
   ```
   👉 El mensaje debe explicar qué hiciste, así tu compañero entiende el cambio.

4. **Sube los cambios a GitHub**  
   ```bash
   git push origin main
   ```
   👉 Esto envía tus cambios a la rama principal (`main`).  
   Si trabajas en otra rama, reemplaza `main` por el nombre de tu rama.

---

## 📌 Ejemplo práctico
Supongamos que editaste tu archivo `index.html` y agregaste una lista de hobbies:
```bash
git add index.html
git commit -m "Añadí lista de hobbies en index.html"
git push origin main
```

---

## 💡 Tip extra
En VS Code también puedes usar la pestaña **Source Control (Control de código fuente)**:
- Ahí verás los archivos modificados.  
- Puedes hacer *commit* escribiendo el mensaje y presionando ✔.  
- Luego haces *push* con el botón de sincronización 🔄.  

