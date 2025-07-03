# 🌤️ Weather App

¡Hola! Esta es una app web simple que te muestra el clima actual de cualquier ciudad que escribas. Fue creada con **HTML, CSS, JavaScript**, y usa la **API de OpenWeatherMap** para obtener los datos en tiempo real.

---

## 🚀 ¿Qué hace?

- Buscas una ciudad (por ejemplo: `Bogotá`, `London`, `Tokyo`)
- Te muestra:
  - Temperatura actual
  - Humedad
  - Velocidad del viento
  - Hora de salida y puesta del sol
  - Icono del clima (soleado, nublado, etc.)

Además, está estilizada para que se vea moderna, responsiva y fácil de usar.

---

## 🛠️ Tecnologías usadas

- [Vite](https://vitejs.dev/) como herramienta de desarrollo
- HTML + CSS puro (con animaciones)
- JavaScript moderno (ES6+)
- [OpenWeatherMap API](https://openweathermap.org/)
- [Axios](https://axios-http.com/) para hacer peticiones HTTP
- [AlertifyJS](https://alertifyjs.com/) para mostrar mensajes bonitos

---

## ⚙️ ¿Cómo usarla?

1. Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/weather-app.git
cd weather-app
```

2. Instala las dependencias:

```bash
npm install
```

3. Crea un archivo `.env` en la raíz del proyecto con tu clave de OpenWeather:

```env
VITE_WEATHER_API=tu_api_key_aqui
```

4. Corre la app localmente:

```bash
npm run dev
```

5. Abre en tu navegador: [http://localhost:5173](http://localhost:5173)

---

## 📦 ¿Cómo subirla a producción?

```bash
npm run build
npm run deploy
```

Esto construye la app y la sube a GitHub Pages (si ya tienes el repositorio configurado).

---

## 📝 Notas finales

- Esta app está pensada como proyecto educativo o personal.
- La clave API se usa desde el frontend, así que **no es privada**. Recomendado solo para pruebas o usar claves con restricciones.
- Puedes personalizar el diseño, idioma o unidades de medida fácilmente.

---

## 🌐 Demo

_Si ya está en línea, pon aquí tu enlace de GitHub Pages:_

👉 [https://tuusuario.github.io/weather-app](https://tuusuario.github.io/weather-app)

---

¡Eso es todo!  
Gracias por visitar el repo 😊
