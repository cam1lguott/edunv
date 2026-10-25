# Instrucciones de Idioma y Comunicación

- Idioma principal: Comunícate, explica y responde en español.
- Documentación y mensajes: Redacta explicaciones, resúmenes, mensajes de estado y comentarios en español a menos que se indique explícitamente lo contrario.

## Notificación Sonora al Finalizar
- Al completar una tarea o respuesta, ejecuta el siguiente codigo corto para emitir un sonido de que finalizó la tarea:
  ```powershell
  [console]::beep(1000, 250)
  ```

## Repositorios y Automatización de Git
- **Proyecto edunv**: Ubicado en `C:\Users\camil\Documents\GitHub\edunv`.
- **Git Push Automático**: Al terminar modificaciones en este repositorio, realiza automáticamente `git add`, `git commit -m "n"` y `git push origin main`. El mensaje del commit siempre debe ser únicamente `"n"`. No le pidas al usuario que use GitHub Desktop ni confirmaciones para hacer push.


