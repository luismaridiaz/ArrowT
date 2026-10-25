# Entrenador Piper Arrow III (PA-28R-201) — Escuela de vuelo

App independiente (no toca las del C172). Tren retráctil, hélice de paso constante (MP + rpm), inyección, dos depósitos con selector, bomba eléctrica, mando circular por defecto, 23 lecciones y 4 checklists (arranque, despegue, aterrizaje GUMP, emergencia).

Publicar: sube la carpeta entera a Netlify Drop / GitHub Pages / Vercel (index.html, manifest.json, sw.js e iconos juntos). Instalar en iPhone: Safari → Compartir → Añadir a pantalla de inicio.

## Límites (honestos)
- Modelo simplificado, NO validado contra un avión real. Inercias y geometría del tren estimadas.
- Contrastado con datos publicados del POH (velocidades: Vs 60/55, Vx 78, Vy 90, Va 118, Vfe 103, Vno 146, Vne 183, tren Vle/Vlo 129 y repliegue 107): coinciden. Ascenso a Vy a peso máximo ~900 fpm en el modelo frente a 831 fpm publicados (~8 % más); crucero ~6 % lento; despegue sobre 50 ft ~1900 ft (publicado ~1600).
- Extensión automática del tren modelada de forma didáctica: selector arriba + IAS < 88 kt + MP < 14,5" en vuelo → tren abajo (botón AUTO = override). Los umbrales son una aproximación mía, no cifras del POH. Valores de procedimiento didácticos: verifícalos con tu POH.
- Solo para aprender procedimientos y sensaciones; no sustituye instrucción real.

## Cambios v2
- Morro de cabina más pequeño.
- Mando elíptico (por defecto) con un solo volante claro estilo Piper: lados = alerones, arriba/abajo = cabeceo. Ajustes permite volver al circular/clásico.
- Palancas con colores de cabina Piper: gas negra, hélice azul, mezcla roja.
- Vista de cabina propia (colores y marcos de cada modelo).
- Panel de mandos y escenario ~1/3 más bajo; instrumentos redondos ocupan el ancho del móvil; (Arrow/L-39) tren como palanca vertical.
