# Conventional-Commit
## Que es conventional commit?

Los *Conventional Commits* son una guia o conjunto de reglas simples que sirven para escribir los mensajes de *commit* de forma *ordenada* y con un formato estandar. 
La idea es que esos mensajes sean faciles de entender para las personas y tambien para las herramientas que analizan el codigo automaticamente.

**commit:** es guardar permanentemente un conjunto de cambios en el historial del repositorio.

**Tipos:**

**fix:** Corregir el error de validacion de password

**feat(api):** Agregar endpoint para obtener el perfil de usuario

**docs:** Cambios en la documentacion (README, comentarios, etc.)

**style:** Reorganiza o mejora el codigo sin cambiar su comportamiento

**refactor:** Agrega o modifica tests

**chore:** Tareas de mantenimiento o configuracion

**perf:** Mejora el rendimiento del codigo

**build:** Cambios que afectan el proceso de build o dependencias

**ci:** Cambios en la integración continua (CI/CD)

**revert:** Revierte un commit anterior

## Por que es importante?

Es importante porque le da *orden* e *inteligencia* al caos natural de los mensajes de commit ya que este: Permite automatizar tareas, facilita el trabajo en equipo, hace que el historial del proyecto sea claro

**Ejemplo**

En vez de poner un mensaje tipo **"arreglo final, final, definitivo"** usas:

**feat:** agregar pantalla de inicio

**fix:** corregir error al iniciar sesion
