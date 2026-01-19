# Curso-de-html-basico
Un pequeño proyecto para poner en práctica lo que hemos aprendido del curso




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
-  se descarga con `git pull origin main`.  
- Si también hace cambios, debe subirlos con `git push origin main`.  

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

