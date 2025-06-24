# Reto JS Interactivo con OpenAI y Fundamentos Clave

## Objetivo General

Construir una app web tipo chat que se conecte con la API de OpenAI **y que esté estructurada para aplicar fundamentos importantes de JavaScript** vistos en las clases:

> * Objetos
> * Hoisting, Scope y Closures
> * Callbacks, Promesas, Async/Await
> * Prototipos, Clases y Modularidad

---

## Requerimientos por célula (mínimo 12 totales)

Cada grupo debe trabajar mínimo un requerimiento por lección, completando en total **al menos 12 requerimientos distribuidos** entre todos:

### Lección 1: Objetos en JavaScript

1. **Modela los mensajes como objetos JS** con propiedades `autor`, `contenido` y `timestamp`.
2. **Crea un historial de conversaciones** que sea un array de objetos mensaje.
3. **Crea una función para renderizar los mensajes** en el DOM usando `.forEach()` sobre el array de objetos.

### Lección 2: Hoisting, Scope, Closures, Callbacks

4. **Demuestra un caso de hoisting**, usando una función declarada antes de ser definida.
5. **Crea una función closure** que permita contar cuántas preguntas ha hecho el usuario.
6. **Implementa un callback** que se ejecute al recibir respuesta de la API (antes de mostrarla en el DOM).

### Lección 3: Promesas, Async/Await, Prototipos, Clases, Modularidad

7. **Consume la API de OpenAI con `async/await`** y estructura bien los `try/catch`.
8. **Crea una clase `ChatMessage`** que modele un mensaje y tenga un método `.formatear()` para mostrarlo bonito.
9. **Agrega una promesa falsa** para simular la carga de mensajes antiguos antes de iniciar el chat (delay artificial).
10. **Modulariza tu código JS en funciones separadas** (`enviarMensaje()`, `renderizarHistorial()`, etc.).
11. **Agrega una función de autocompletado** usando `setTimeout()` para simular procesamiento AI (como typing delay).
12. **Maneja estados de carga y errores en pantalla** como mensajes de "Cargando..." o "Error de conexión".

---

## Entregables

* Repositorio Git con el código fuente.
* `index.html` con estructura básica del chat.
* `main.js` con toda la lógica.
* (Opcional) `style.css` si se desea estilizar.
* Archivo README con descripción del proyecto, división de tareas por célula y explicación breve de cada requerimiento aplicado.

---


## Convenciones y buenas prácticas

Consulta las [convenciones de nombramiento y buenas prácticas](./README-CONVENCIONES.md) para ramas, CSS y JavaScript en este repositorio.

En ese archivo encontrarás:
- Convenciones para nombrar ramas según tickets de Azure DevOps.
- Buenas prácticas para nombrar IDs y clases CSS.
- Buenas prácticas para variables y clases en JavaScript.

## Recursos sugeridos

* Documentación API: [https://platform.openai.com/docs/guides/text?api-mode=chat](https://platform.openai.com/docs/guides/text?api-mode=chat)
* Cómo usar `fetch`: [https://developer.mozilla.org/es/docs/Web/API/Fetch_API](https://developer.mozilla.org/es/docs/Web/API/Fetch_API)
* Scope y closures: [https://developer.mozilla.org/es/docs/Web/JavaScript/Closures](https://developer.mozilla.org/es/docs/Web/JavaScript/Closures)
* Async/Await: [https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/async\_function](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/async_function)

---

## 🧪 Se tendra en cuenta


* La correcta conexión con la API y visualización en el DOM.
* La implementación clara de los 12 requerimientos JS.
* Que cada célula haya trabajado una parte concreta del reto.
* Buenas prácticas de estructura y código limpio.

