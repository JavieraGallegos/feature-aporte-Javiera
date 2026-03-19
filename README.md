# Actividad Branching Git

## Integrantes
# 1 Diego Castillo.
# 🌿 ¿Qué es una rama en Git?

## 📌 Definición
- **Qué es una branch:**  
  Una rama (*branch*) en Git es una copia independiente del código donde puedes trabajar sin afectar la versión principal del proyecto.

## 🎯 ¿Para qué sirve?
- Permiten separar tareas sin mezclar todo el trabajo.

## ⚠️ ¿Qué problema resuelve?
- Evitan romper el código principal mientras se desarrollan nuevas funcionalidades.

## 🚫 ¿Por qué no trabajar siempre en `main`?
- Porque la rama `main` debe mantenerse estable y sin errores.

---

## 💡 Ejemplo

Estás desarrollando una página web en Git.  
Tienes la rama `main` funcionando correctamente, pero necesitas agregar un login.

En lugar de trabajar directamente en `main`:

- Creas una rama llamada `login`
- Desarrollas el login ahí
- Si hay errores, no afectan el proyecto principal
- Cuando todo funciona bien, unes la rama a `main`

---
...

## ✅ Conclusión



Las ramas son fundamentales porque permiten trabajar de forma ordenada y segura, evitando errores en el código principal y facilitando el desarrollo en equipo.
- Alumno 2
- Alumno 3
- Alumno 4
- Alumno 5
-------
------
- ## 1. ¿Qué es un Pull Request?

Un **Pull Request (PR)** es una solicitud para integrar cambios de una rama a otra (por ejemplo, de `feature/pull` a `main`) en plataformas como GitHub.

No es solo subir código, sino pedir revisión antes de unirlo al proyecto principal.

---

## 2. ¿Para qué sirve en trabajo colaborativo?

Sirve para que los integrantes del equipo puedan:

- Revisar el código de otros  
- Comentar y sugerir mejoras  
- Detectar errores antes de integrar cambios  

Permite trabajar en paralelo sin afectar la rama principal.

---

## 3. ¿Por qué es importante revisar antes de hacer merge?

Porque ayuda a:

- Evitar bugs o errores  
- Mantener buena calidad de código  
- Asegurar que los cambios cumplen con lo esperado  

---

👉 **En resumen:** el PR actúa como un filtro de calidad antes de unir cambios.
-----
----
- Alumno 7
- Alumno 8

---

# Respuesta-Alumno-DiegoContreras

1. ¿Que es un merge?

 El merge en github es la fusión de ramas que generalmente es la rama main para poder incorporar el código nuevo al proyecto.

2. ¿Qué es un conflicto de merge?

 Esto ocurre cuando se editaron en la misma linea de código del mismo archivo de formas distintas. 
 Pensandolo como programador: El programador (Diego) edito código en la linea 20 de un archivo html y el programador (David)    hizo modificaciones en la misma linea, en este punto git se detiene y va a decir: "cúal versión debo guardar?, la de Diego o   David, eso lo decides tú"

3. ¿Cómo puede evitarse o reducirse?

   1. Comunicación con el equipo
      Avisar antes de trabajar en un archivo o feature. Un simple mensaje en el canal del equipo evita que dos personas toquen        lo mismo al mismo tiempo.
      
   2. Trabajar en ramas pequeñas y cortas
      Mientras más tiempo viva una rama sin mergearse, más probabilidad de conflicto. Lo ideal es hacer ramas enfocadas en una        sola tarea y mergearlas rápido.

   3. Hacer pull frecuente
      Antes de empezar a trabajar y durante el desarrollo, traer los últimos cambios del repositorio:
      bashgit pull origin main
      Así tu rama siempre está actualizada con lo que hicieron los demás.

   4. Dividir bien el trabajo
      Cada persona trabaja en archivos o módulos distintos. Si el equipo tiene clara la separación de responsabilidades, los          conflictos bajan mucho.
   






