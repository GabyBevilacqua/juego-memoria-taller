# Juego de Memoria (React)

Proyecto de estudio desarrollado con React para practicar lógica de juego, manejo de estado y renderizado dinámico en el navegador.

El objetivo es descubrir todos los pares de cartas con emojis. Cuando se completan todas las coincidencias, se muestra un mensaje de éxito.

## Demo del proyecto

- Vercel: `https://vercel.com/gaby-bevilacquas-projects/juego-memoria-taller`

## Tecnologías usadas

- React
- JavaScript (ES6+)
- CSS3 (animaciones con keyframes)
- SweetAlert2 (alerta de victoria)
- Webpack + Babel

## ¿Qué hace la app?

- Muestra una grilla de cartas con símbolos ocultos.
- Permite seleccionar hasta 2 cartas por turno.
- Comprueba si ambas cartas coinciden.
- Si coinciden, quedan descubiertas.
- Si no coinciden, se vuelven a ocultar.
- Cuando todas las cartas están emparejadas, muestra una alerta de “juego completado”.
- Incluye botón para volver a jugar y mezclar cartas nuevamente.

## Lo aprendido con este proyecto

Este proyecto me ayudó a reforzar conceptos clave de Frontend y React:

- Uso de `useState` para manejar estados del juego (cartas, selección actual, cartas acertadas).
- Uso de `useEffect` para reaccionar a cambios de estado y ejecutar la lógica de validación.
- Renderizado condicional para mostrar carta descubierta u oculta según su estado.
- Manejo de eventos (`onClick`) para la interacción del usuario.
- Lógica de comparación de pares y control del flujo por turnos.
- Importancia de reiniciar estado correctamente al empezar una nueva partida.
- Aplicación de animaciones CSS para mejorar la experiencia visual.
- Integración de librerías externas (SweetAlert2) para feedback al usuario.

Además, fue una buena práctica para entender cómo separar responsabilidades entre:

- lógica del componente,
- estructura visual (JSX),
- estilos y animaciones (CSS).

## Estructura principal

```text
src/
	js/
		index.js
		component/
			home.jsx
	styles/
		index.css
```

## Instalación y ejecución local

1. Instalar dependencias:

```bash
npm install
```

2. Iniciar entorno de desarrollo:

```bash
npm run start
```

3. Generar build de desarrollo:

```bash
npm run build
```

## Deploy

Para publicar en GitHub Pages:

```bash
npm run deploy:github
```

También puedes desplegar en Vercel siguiendo la guía del proyecto en `docs/DEPLOY.md`.

## Próximas mejoras (ideas)

- Contador de movimientos.
- Temporizador por partida.
- Niveles de dificultad (más cartas).
- Persistir récord (mejor tiempo o menos movimientos).
- Mejoras de accesibilidad (teclado, focus, contraste).

## Autoría

Proyecto realizado como práctica personal para consolidar fundamentos de React y lógica de programación aplicada a juegos simples.
