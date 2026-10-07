# test-simple-stock-flow-page

> **Prueba técnica · Ficha ADSO 3413974**  
> Sitio público estático de presentación de Simple Stock Flow.

---

### 1. Qué es esto
Es el sitio web estático público que presenta la solución *Simple Stock Flow*, sus principios de diseño y sus afirmaciones de negocio. Por mandato explícito de la especificación técnica, **este sitio no consume ni se comunica con la API**; es totalmente autónomo y estático.

### 2. Cómo se levanta
No requiere compilación ni dependencias. Puede abrirse directamente en cualquier navegador o servirse con un servidor estático:
```bash
# Abrir directamente en el navegador
start index.html

# O utilizando un servidor simple local
npx serve .
```

### 3. Dónde están los datos
Este repositorio no contiene bases de datos ni almacena estados dinámicos. Toda la información presentada es fija en el código HTML/CSS.

### 4. Cómo se prueba
Basta con abrir `index.html` en un navegador web y verificar que la estructura visual, las secciones y los estilos se renderizan correctamente sin errores de consola.

### 5. Qué falta
El sitio estático de presentación está 100% completo y listo para despliegue público.