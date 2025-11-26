# Documentación del Lenguaje Markdown

Este documento contiene la **referencia completa de comandos Markdown**, organizada por categorías y con múltiples ejemplos prácticos para aprender y usar el lenguaje de marcado más utilizado en GitHub.

---

##  1. Encabezados

Markdown usa el símbolo `#` para crear títulos jerárquicos.

```markdown
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

---

### 2. Formato de texto 

Sirve para resaltar contenido, aplicar negritas, cursivas, tachado, subrayar o combinar estilos. 

**Negritas**
*Cursiva*
***Negritas + cursiva***
~~Tachado~~
<u>Subrayado</u>

Ejemplo
Esto es **importante**, esto es *cursivo*, y esto está ~~incorrecto~~ corregido.

---

#### 3. Citas

Permiten destacar texto como referencias, comentarios o notas importantes.

Ejemplo 

> Esto es una cita.
> Puede ocupar varias líneas.

Eemplo con citas anidadas 
> Nivel 1
>> Nivel 2
>>> Nivel 3

---

##### 4. Listas

Se usan para organizar información en elementos ordenados, no ordenados o listas de tareas.

Ejemplo no ordenadas
- Item 1
- Item 2
  - Sub-item

Ejemplo ordenadas
1. Paso 1
2. Paso 2
3. Paso 3

Ejemplo tarea
- [x] Hecho
- [ ] Pendiente

---

###### 5. Enlaces e Imágenes

Permiten conectar a sitios web o mostrar imágenes mediante URL.

Ejemplo enlaces 
[Ir a Google](https://google.com)

Ejemplo imagenes 
![Logo Markdown](https://markdown-here.com/img/icon256.png)

Con titulo 
![Logo](url "Título de la imagen")

---

####### 6. Código

Se utiliza para mostrar comandos, ejemplos de programación o fragmentos de código.

Ejemplo codigo en linea 
`console.log("Hola mundo");`

Ejemplo bloques de código
```javascript
function saludo() {
  console.log("Hola desde JS");
}
saludo();

---

####### 7. Tablas  
Sirven para organizar datos en filas y columnas.

# Ejemplo  

```markdown
| Nombre | Edad | País   |
|--------|------|--------|
| Ana    | 20   | México |
| Luis   | 22   | Perú   |

####### 8. Líneas divisorias

Separan secciones dentro de un documento.

## Ejemplo 
---
***
___

---

###### 9. Escape de caracteres

Permite mostrar caracteres que normalmente generan formato.

### Ejemplo

\*No es cursiva\*
\# No es un título
\_Texto con guion bajo\_

---

###### 10. Bloques de texto literal

Muestran texto exactamente como se escribe, sin interpretación Markdown.

##### Ejemplo 

Este texto se muestra tal cual
Sin formato aplicado

