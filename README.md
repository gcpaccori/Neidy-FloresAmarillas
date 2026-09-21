# Neidy · Mi universo amarillo

Una dedicatoria 3D para Neidy, por el 21 de septiembre de 2026. Hecha para explorar con el dedo desde un celular.

## La experiencia

- Seis capítulos: despertar, galaxia, palabras, corazón, promesa y dedicatoria.
- 156 flores tridimensionales con 22 pétalos cada una, centros y semillas en relieve.
- 240 expresiones de cariño, 4 500 partículas doradas y 1 700 estrellas.
- Mantener, deslizar, tocar y dibujar desbloquean los capítulos; botones alternativos para teclado y gestos simples.
- Transiciones con bloqueo temporal para evitar saltarse las sorpresas.
- Música ambiental sintetizada, opcional y activada por la persona que visita la página.
- Movimiento suave, respeto a `prefers-reduced-motion`, pausa en segundo plano y mensaje alternativo si WebGL no está disponible.
- Solo usa el nombre Neidy. Sin apellidos, formularios, analítica ni servicios externos durante la visita.

## Abrir en desarrollo

Requiere Node.js 20.19+ o 22.12+.

```sh
npm ci
npm run dev
```

## Publicar

`dist/` es la web completa, lista para cualquier alojamiento estático con HTTPS. No requiere compilación ni claves. La biblioteca Three.js 0.180.0 está incluida localmente bajo licencia MIT, en `dist/vendor/`.

Para GitHub Pages: en Settings → Pages, seleccionar GitHub Actions y ejecutar el flujo incluido. El flujo es manual para no cambiar la audiencia al subir el código.

## Personalizar

Los mensajes están en `chapters`, `names` y `lines` en `dist/app.js`. Los colores y medidas están en `dist/style.css`.

## Verificación

Sintaxis JavaScript y archivos locales verificados. La revisión visual e interacción en un navegador real quedó pendiente porque el navegador de pruebas bloqueó el acceso a la vista local. Se recomienda comprobar Chrome Android y Safari iOS, especialmente audio, presión prolongada y rendimiento en dispositivos de gama baja.

No se necesita instalar dependencias en producción. Vite se usa exclusivamente para desarrollo.
