# Limpieza de áreas comunes · Edificio B Tepetlapa

Página de **solo consulta** para los inquilinos. Muestra cuánto se ha cobrado, quién ha pagado cada mes y el saldo.
Nadie puede modificarla desde la página: los datos viven en `data.json` y solo cambian cuando tú subes un archivo nuevo.

## Publicarla (una sola vez)
1. En github.com crea un repositorio nuevo (por ejemplo `limpieza-edificio-b`).
2. Entra a **Add file → Upload files** y sube `index.html`, `data.json` y este `README.md`. Confirma con **Commit changes**.
3. Ve a **Settings → Pages**. En *Build and deployment* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
4. Espera uno o dos minutos. GitHub te mostrará la dirección, algo como `https://TU-USUARIO.github.io/limpieza-edificio-b/`. Esa es la que compartes con los vecinos.

Para que nadie más que tú pueda cambiar el repositorio, no agregues colaboradores. Los vecinos solo necesitan el enlace de la página.

## Actualizarla cada vez que cobres
1. Abre `admin.html` en tu computadora (doble clic). **No lo subas a GitHub.**
2. Registra los pagos: toca el cuadro del depto y el mes, y elige «Pagó cuota». «Todos» marca todo el mes de una vez.
3. Pulsa **Guardar data.json para GitHub**. Se descarga un archivo `data.json`.
4. En tu repositorio abre `data.json`, pulsa el lápiz o **Add file → Upload files**, sube el nuevo y confirma con **Commit changes**.
5. En un minuto los vecinos ven los cambios.

## Importante
- `admin.html` guarda tus datos en el navegador donde lo abres. Usa siempre el mismo navegador y haz un **Respaldo completo** de vez en cuando. Con **Cargar archivo** lo recuperas.
- Si cambias de computadora, carga ahí tu respaldo completo.
- Un repositorio público y su página los puede ver cualquier persona con el enlace. Por eso la página muestra solo números de departamento y no los nombres. Los nombres no salen en `data.json`. Si quieres mostrarlos, actívalo en Ajustes de `admin.html`.
