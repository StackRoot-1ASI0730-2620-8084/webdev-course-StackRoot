# Guiones de video: Fundamentos de Desarrollo Web

**Curso introductorio de HTML y CSS para estudiantes de secundaria (12 a 17 años)** · 1ASI0730 Aplicaciones Web

---

## 1. Plan general del curso

El curso se divide en **8 videos** (el enunciado permite de 5 a 10 lecciones de 5 a 15 minutos) con una duración total de **60 minutos**. Cada video cubre uno o dos temas del enunciado, va de lo más simple a lo más completo y termina con una práctica en un editor en línea. Las pausas de práctica las hace el estudiante: el video solo muestra la indicación, por eso no se cuentan en la duración.

| # | Video | Tema del enunciado | Duración | Responsable |
|---|-------|--------------------|----------|-------------|
| 1 | ¿Qué es un sitio web? | Introducción al desarrollo web | 5:00 | Integrante 1 |
| 2 | Tu primera página: la estructura HTML | Estructura HTML básica (etiquetas, elementos, atributos) | 8:00 | Integrante 2 |
| 3 | Títulos, párrafos y listas | Elementos HTML comunes (I) | 7:00 | Fabricio |
| 4 | Imágenes y enlaces | Elementos HTML comunes (II) | 7:00 | Fabricio |
| 5 | Dale estilo con CSS | Introducción a CSS (selectores, propiedades) | 9:00 | Ingrid |
| 6 | Centrar, colores y bordes | Estilo simple | 8:00 | Ingrid |
| 7 | Construye tu página de perfil | Creación de una página web básica | 11:00 | Integrante 5 |
| 8 | Errores comunes y próximos pasos | Recomendaciones y errores comunes | 5:00 | Integrante 1 |
|   | **Total** | | **60:00** | |

El reparto es una sugerencia: cada responsable redacta el guion final, graba la narración y la pantalla de sus videos; el líder revisa que todo cumpla la rúbrica y completa el Reporte de participación.

---

## 2. Pautas de producción y de lenguaje

- **Solo herramientas en línea y gratuitas**: todo el código se muestra en JSFiddle (https://jsfiddle.net/). Para visualizar los cambios, pulsa **Run** (Ejecutar). Los estudiantes no necesitan cuenta ni instalar nada. Los enlaces a los editores precargados van en la descripción de cada video. Antes de grabar, comprueben que cada ejemplo cargue en JSFiddle y que el botón Run actualice la vista de resultado. Los enlaces de ejercicios deben prepararse y probarse previamente.
- **Videos no listados en YouTube**. Título sugerido: «Lección N: nombre del video».
- **Terminología (Anexo C del enunciado)**: usar «biblioteca», «requisito» y «aplicación»; evitar «librería», «requerimiento», «aplicativo», «apartado» (usar «sección») y «metodología» (usar «método» o «marco de trabajo»). No usar formas como «testear», «deployar» o «comitear».
- **Estilo**: …

---

## Video 1 · ¿Qué es un sitio web? 

**Objetivo**: entender qué es un sitio web, cómo llega a la pantalla y qué papel cumplen HTML y CSS.

**Enlace en la descripción**: JSFiddle del Ejercicio 1 (Explorar un sitio web).

### Escena 1 · Bienvenida 

**En pantalla**: título animado «Fundamentos de Desarrollo Web» y los íconos de Chrome, Firefox, Safari y Edge.

> ¡Hola! Te doy la bienvenida a este curso. Durante la próxima hora vas a crear tu propia página web desde cero. Y lo mejor: no necesitas instalar nada ni saber programar. Solo necesitas un navegador, como Chrome, Firefox, Safari o Edge. Piensa en tu sitio web favorito: un juego, un canal, una tienda... Alguien lo construyó, y tú también vas a poder hacerlo. ¿Empezamos?

### Escena 2 · ¿Qué es un sitio web? 

**En pantalla**: animación en tres pasos: una laptop envía una flecha con la palabra «pedido» a una computadora grande (servidor) y recibe de vuelta una flecha «respuesta» con la página. Texto en pantalla: «URL = la dirección de una página».

> Un sitio web es un conjunto de páginas conectadas entre sí que puedes ver desde un navegador. Esas páginas están guardadas en computadoras especiales llamadas servidores, que están encendidas todo el día. Imagina un restaurante. Tú haces un pedido: escribes una dirección, que se llama URL. El servidor es la cocina: recibe tu pedido y te devuelve el plato. Ese plato son los archivos de la página, y el navegador se encarga de servírtelos en tu pantalla. Todo ocurre en menos de un segundo.

### Escena 3 · HTML y CSS 

**En pantalla**: dibujo de una casa solo con paredes, puertas y ventanas (etiqueta «HTML»); luego la misma casa pintada y decorada (etiqueta «CSS»). Después, pantalla dividida: una página sin estilo a la izquierda y la misma página con estilo a la derecha. Cierra con la fórmula «Sitio web = contenido (HTML) + estilo (CSS)».

> ¿De qué está hecha una página? Principalmente de dos lenguajes. El primero es HTML. Sirve para poner el contenido y la estructura: títulos, textos, imágenes y enlaces. Es como las paredes, las puertas y las ventanas de una casa. El segundo es CSS, que se encarga del estilo: colores, tipos de letra, tamaños y bordes. Es la pintura y la decoración de esa casa. Mira: esta es la misma página sin CSS y con CSS. La información es idéntica, pero el estilo la cambia por completo. Entonces recuerda esta fórmula: sitio web es igual a contenido, que es HTML, más estilo, que es CSS. Existe un tercer lenguaje, JavaScript, que añade acciones y movimiento, pero ese lo dejamos para otro curso.

### Escena 4 · Mira por dentro

**En pantalla**: grabación del navegador en una página pública sencilla (por ejemplo, un artículo de Wikipedia). Clic derecho sobre un título, opción «Inspeccionar», doble clic sobre el texto del título y se escribe otro. Texto en pantalla: «Solo cambia en tu pantalla. Al recargar, todo vuelve a la normalidad».

> Vamos a espiar una página por dentro. Hago clic derecho sobre un título y elijo «Inspeccionar». Aquí aparece el código HTML de esta página. Si hago doble clic sobre el texto, puedo cambiarlo... ¡mira! El título cambió. Pero tranquilo: solo cambió en mi pantalla y solo por un momento. Si recargo la página, todo vuelve a la normalidad. No estoy dañando nada: es como dibujarle bigotes a una foto en tu propia pantalla. Es una forma genial de curiosear cómo está hecha cualquier página.

### Escena 5 · Herramientas y práctica 
**En pantalla**: abrir JSFiddle con HTML y CSS precargados. Señalar cada panel y el botón Run. Cambiar en directo el texto del h1, ejecutar, modificar background-color y volver a ejecutar. Cierre: «Pausa y prueba: tu título y tu color».

> «En JSFiddle tenemos un espacio para HTML, otro para CSS y un panel donde aparece la página. Primero busca en HTML el título que dice “Bienvenido a mi página”. Cambia esas palabras por “Mi primera aventura web” y pulsa Run. ¿Ves el nuevo título? Ahora ve a CSS: encuentra background-color: lightblue; y cambia lightblue por lightyellow. Pulsa Run otra vez. ¡El fondo cambió! HTML controla lo que dice la página y CSS cómo se ve. Ahora pausa y prueba: escribe tu propio título y elige otro color. Después ejecuta para comprobar los dos cambios».

---

## Video 2 · Tu primera página: la estructura HTML 

**Objetivo**: distinguir etiqueta, elemento y atributo, conocer el esqueleto de toda página y escribir los primeros elementos.

**Enlace en la descripción**: JSFiddle del Ejercicio 2 (Mi primera página).

### Escena 1 · Repaso y objetivo 

**En pantalla**: resumen del video 1 en una frase y el título «Hoy: etiquetas, elementos y atributos».

> Bienvenido de nuevo. En el video anterior viste que HTML es el esqueleto de una página. Hoy aprenderás cómo se escribe: qué son las etiquetas, los elementos y los atributos, y cuál es la estructura que tiene toda página web. Al final escribirás tu primera página.

### Escena 2 · Etiquetas y elementos 

**En pantalla**: animación de la línea `<p>Hola, mundo</p>`. Se resalta en colores la etiqueta de apertura `<p>`, el contenido «Hola, mundo» y la etiqueta de cierre `</p>`. Una llave debajo de todo el conjunto dice «elemento». Analogía visual: una caja que se abre, se llena y se cierra.

> HTML significa «lenguaje de marcado de hipertexto». Suena complicado, pero la idea es simple: le ponemos marcas al texto para decirle al navegador qué es cada cosa. Esas marcas se llaman etiquetas y se escriben entre los símbolos menor que y mayor que. Mira esta: la letra p entre esos símbolos es la etiqueta de apertura y significa «aquí empieza un párrafo». Luego va el contenido: «Hola, mundo». Y al final, la etiqueta de cierre, igual que la de apertura pero con una barra inclinada. Todo junto, apertura, contenido y cierre, se llama elemento. Piensa en una caja: la etiqueta de apertura es abrirla, el contenido es lo que guardas dentro y la etiqueta de cierre es taparla. Si olvidas cerrar la caja, el navegador se confunde.

### Escena 3 · Atributos 

**En pantalla**: la etiqueta `<html lang="es">` con tres flechas: «nombre del atributo» (lang), «signo igual» y «valor entre comillas» («es»).

> Algunas etiquetas aceptan información extra, que se llama atributos. Se escriben dentro de la etiqueta de apertura: primero el nombre, luego el signo igual y luego el valor entre comillas. Por ejemplo, el atributo lang con el valor «es» le dice al navegador que esta página está en español. Más adelante usaremos atributos para elegir qué imagen mostrar o a dónde lleva un enlace.

### Escena 4 · El esqueleto de toda página 
**En pantalla**: el código completo aparece línea por línea, con cada parte resaltada mientras se menciona. A la derecha, un diagrama de dos bloques: «head: lo que no se ve» y «body: lo que sí se ve».

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi primera página</title>
  </head>
  <body>
    <h1>Hola, mundo</h1>
  </body>
</html>
```

> Toda página web tiene el mismo esqueleto. La primera línea, doctype html, le avisa al navegador que usaremos HTML moderno. Después viene el elemento html, que envuelve toda la página. Dentro hay dos partes. La cabeza, llamada head, guarda información que no se ve en la página: la codificación de caracteres, para que se vean bien las tildes y la eñe, y el título, que aparece en la pestaña del navegador. Y el cuerpo, llamado body, que es todo lo que sí ves: textos, imágenes y enlaces. Cabeza para lo que no se ve, cuerpo para lo que sí se ve. Fíjate también en la sangría: cada elemento que está dentro de otro se escribe un poco más a la derecha. No es obligatorio, pero te ayuda a leer tu código.

### Escena 5 · Demostración en JSFiddle 

**En pantalla**: JSFiddle con zoom grande. Texto en pantalla: «En JSFiddle, lo que escribes en el panel HTML va dentro del body».

> Vamos a practicar en JSFiddle. Abre el enlace de la descripción. Verás los paneles HTML, CSS y JavaScript, y un espacio para el resultado. Para ver los cambios, pulsa Run (Ejecutar). Hoy solo usaremos el panel HTML. Un detalle: JSFiddle ya prepara el esqueleto por nosotros, así que lo que escribimos en el panel HTML es lo que va dentro del body. Escribo la etiqueta h1, el texto «Mi primera página» y cierro la etiqueta. Pulso Run (Ejecutar) y mira cómo aparece en el panel de resultado. Ahora agrego un párrafo con la etiqueta p: «Soy Alex y estoy aprendiendo a crear páginas web». Fíjate que uso un apodo, no mi nombre completo: en internet es mejor cuidar tus datos. Ahora voy a borrar a propósito la barra de la etiqueta de cierre del párrafo... ¡mira cómo se desordena todo! El navegador intentó adivinar lo que yo quería. Por eso, cada etiqueta que abres, ciérrala.

### Escena 6 · Práctica y cierre 

**En pantalla**: mostrar en JSFiddle cómo se escriben un h1 y dos p, ejecutar con Run y quitar y recuperar una etiqueta de cierre. Tarjeta final: «Pausa y prueba: cambia el apodo y escribe tus dos frases».

> «Primero escribimos `<h1>Alex</h1>`. h1 indica que este es el título principal. Pulso Run y aparece arriba. Debajo agrego `<p>Me gusta dibujar.</p>`: p significa párrafo. Escribo otro: `<p>Estoy aprendiendo HTML.</p>`. Ejecutamos y vemos las tres líneas. Fíjate en que cada elemento tiene apertura, contenido y cierre. Si quito el cierre de un párrafo, el navegador puede interpretar el contenido de forma inesperada; lo recupero para mantener el código claro. Ahora pausa: cambia Alex por un apodo inventado y sustituye las dos frases por tus gustos. Pulsa Run y comprueba que se muestran correctamente».

---

## Video 3 · Títulos, párrafos y listas 

**Objetivo**: usar encabezados, párrafos, texto resaltado y listas ordenadas y sin orden.

**Enlace en la descripción**: JSFiddle del Ejercicio 3 (Mi pasatiempo favorito).

### Escena 1 · Repaso 

**En pantalla**: esqueleto de página con el body resaltado.

> ¡Hola otra vez! Ya sabes escribir un elemento y conoces el esqueleto de una página. Hoy vas a aprender los elementos que más vas a usar: títulos, párrafos, textos resaltados y listas.

### Escena 2 · Títulos y párrafos 

**En pantalla**: a la izquierda, la imagen del índice de un libro (capítulo, sección, subsección); a la derecha, JSFiddle donde se escribe el código. Texto en pantalla: «Un solo h1 por página».

> Los títulos en HTML se llaman encabezados y hay seis niveles: h1, h2, h3, y así hasta h6. Piensa en el índice de un libro: el h1 es el título del libro y solo debe haber uno por página. Los h2 son los capítulos y los h3 son las secciones dentro de cada capítulo. Vamos a escribir una página sobre un pasatiempo. Escribo un h1: «Mi pasatiempo favorito», y debajo un h2: «¿Por qué me gusta?». Ahora un párrafo con la etiqueta p que explica la razón. Fíjate: el h1 se ve más grande que el h2. Pero ojo: nunca elijas un encabezado solo por su tamaño. El tamaño lo cambiaremos después con CSS. El nivel del encabezado indica qué tan importante es el texto, y eso ayuda a los buscadores y a las personas que usan lectores de pantalla. Otro detalle: si en tu código presionas Enter muchas veces, el navegador lo ignora. Para separar ideas, crea un nuevo párrafo.

### Escena 3 · Resaltar texto 

**En pantalla**: el párrafo con una palabra dentro de `<strong>` y otra dentro de `<em>`; el resultado se ve en negrita y en cursiva.

> Dentro de un párrafo puedes resaltar palabras. Con la etiqueta strong, el texto se ve en negrita y significa «esto es importante». Con la etiqueta em, se ve en cursiva y da énfasis. Escribo: «Me gusta mucho el fútbol y casi siempre juego los sábados», poniendo cada palabra dentro de su etiqueta. Pruébalo y mira el resultado.

### Escena 4 · Listas 

**En pantalla**: JSFiddle. Se escribe una lista sin orden y luego se cambian ul por ol (apertura y cierre) para ver las viñetas convertirse en números. Texto en pantalla: «ul = viñetas · ol = números · li = cada ítem».

> Para hacer listas hay dos opciones. La lista sin orden, con la etiqueta ul, muestra viñetas. La lista ordenada, con la etiqueta ol, muestra números. Dentro de cualquiera de las dos, cada ítem va en su propio elemento li, que viene de «list item». Escribo un h2: «Mis tres razones». Ahora abro una ul y escribo tres li: «Me divierte», «Me relaja» y «Lo hago con mis amigos». Y ahora cambio ul por ol. ¡Mira! Las viñetas se convirtieron en números. Y recuerda cambiar también la etiqueta de cierre. Una regla fácil: si el orden importa, como los pasos de una receta, usa ol; si no importa, como una lista de cosas que quieres comprar, usa ul.

### Escena 5 · Práctica y cierre 

**En pantalla**: construir en JSFiddle un h1, dos h2, dos párrafos y una lista de tres li. Ejecutar después de cada bloque. Tarjeta final: «Pausa y prueba: cambia el pasatiempo y convierte ul en ol».

> «Vamos por partes. Primero escribo `<h1>Mi pasatiempo favorito</h1>`: es el título principal. Luego `<h2>¿Por qué me gusta?</h2>` y un párrafo con la explicación. Pulso Run para ver cómo se ordenan. Agrego otro h2, “Mis tres razones”, y debajo una lista ul. Cada razón va entre etiquetas li: “Me divierte”, “Me relaja” y “Aprendo cosas nuevas”. Ejecutamos: aparecen viñetas. Si cambio ul por ol, tanto al abrir como al cerrar, aparecen números. Ahora pausa: elige tu propio pasatiempo, cambia las razones y prueba los dos tipos de lista. ¿Cuál usarías si el orden de los pasos fuera importante?».

---

## Video 4 · Imágenes y enlaces 

**Objetivo**: insertar imágenes con texto alternativo y crear enlaces con atributos.

**Enlace en la descripción**: JSFiddle del Ejercicio 4 (Mis favoritos con imagen y enlace).

### Escena 1 · Repaso

**En pantalla**: la página del Ejercicio 3 terminada.

> Hola de nuevo. Tu página ya tiene títulos, párrafos y listas, pero todavía le faltan dos ingredientes que hacen especial a la web: las imágenes y los enlaces.

### Escena 2 · Imágenes 
**En pantalla**: JSFiddle. Se escribe la línea de código y aparece la imagen en el resultado. Flechas con los nombres de los atributos src, alt y width. Texto en pantalla: «Usa imágenes propias o con licencia libre».

```html
<img src="https://picsum.photos/id/10/400/250" alt="Bosque junto a un lago" width="300">
```

> Para mostrar una imagen usamos la etiqueta img. Es especial: no tiene etiqueta de cierre ni contenido, porque la imagen no es texto. En cambio, usa atributos. El atributo src, de «source», o fuente, indica dónde está la imagen: es una dirección web. El atributo alt es un texto alternativo que describe la imagen con palabras. Sirve para que las personas que no pueden ver la pantalla sepan qué hay en la foto, y también se muestra si la imagen no carga. Con width puedo elegir el ancho en píxeles: si lo cambio a 150, la imagen se hace más pequeña. ¿De dónde saco imágenes? Puedes usar dibujos o fotos tuyas, o buscar imágenes de licencia libre. Nunca uses fotos de otras personas sin su permiso.

### Escena 3 · Enlaces 

**En pantalla**: JSFiddle. Se escribe el enlace y se hace clic en el resultado. Se resalta href, el texto del enlace y el atributo target.

```html
<a href="https://developer.mozilla.org/es/" target="_blank">Aprende más en MDN</a>
```

> Los enlaces se crean con la etiqueta a, de «ancla». Necesita el atributo href, que es la dirección a la que llegarás, y entre las etiquetas va el texto donde se hace clic. Escribo un enlace a MDN, una página donde se explica todo sobre desarrollo web. Fíjate en el texto: describe a dónde lleva el enlace. Evita escribir solo «haz clic aquí». Por defecto, el enlace se abre en la misma pestaña. Si quieres que se abra en una pestaña nueva, agrega el atributo target con el valor guion bajo blank. Y un truco: si pones una imagen dentro de un enlace, la imagen también funciona como botón para hacer clic.

### Escena 4 · Práctica y cierre

**En pantalla**: escribir en JSFiddle una imagen con src, alt y width; ejecutar; añadir enlace con href y target; ejecutar y probar el enlace. Cierre: «Pausa y prueba: describe la imagen y personaliza el enlace».

> «Partimos de nuestra página anterior. Agrego una etiqueta img. En src escribo la dirección de la imagen; en alt, una descripción breve como “Bosque junto a un lago”; y con width="300" ajusto su ancho. Pulso Run: ¡ya se ve! Ahora escribo `<a href="https://developer.mozilla.org/es/" target="_blank">Aprender en MDN</a>`. La dirección va en href y las palabras visibles van entre las etiquetas. Ejecutamos y probamos el enlace. Ahora pausa: cambia el ancho a 200 y observa la diferencia; después escribe un texto alternativo que realmente describa la imagen y cambia el texto del enlace sin borrar su dirección».

---

## Video 5 · Dale estilo con CSS 

**Objetivo**: entender qué es CSS, cómo se escribe una regla y usar selectores (de elemento y de clase) con propiedades de color y fuente.

**Enlace en la descripción**: JSFiddle del Ejercicio 5 (Estilo a mi página).

### Escena 1 · Repaso y objetivo

**En pantalla**: la página del Ejercicio 4 sin estilo, con fondo blanco y letra negra.

> ¡Hola! Mira tu página: tiene todo el contenido, pero se ve muy simple. Hoy vas a transformarla con CSS. Aprenderás cómo se escribe una regla de estilo, qué son los selectores y cómo cambiar colores y tipos de letra.

### Escena 2 · Anatomía de una regla CSS 

**En pantalla**: animación de la regla de abajo. Se resalta cada parte con un color y una etiqueta: «selector», «propiedad», «valor», «punto y coma» y «llaves». Analogía visual: una nota que dice «a todos los títulos: pónganse azules».

```css
h1 {
  color: blue;
}
```

> CSS significa «hojas de estilo en cascada». Una regla de CSS funciona como una instrucción: «a todos los títulos, pónganse azules». Se escribe en tres partes. Primero, el selector, que dice a quién le vamos a dar estilo; aquí es h1, o sea, todos los títulos principales. Después, entre llaves, va la propiedad, que es lo que quiero cambiar, en este caso el color. Luego, dos puntos y el valor, que es cómo quiero que quede: azul. Y la línea termina con un punto y coma. Selector, propiedad y valor: esa es la fórmula. Un consejo: si olvidas el punto y coma o una llave, la regla no funciona.

### Escena 3 · ¿Dónde escribo el CSS? 

**En pantalla**: a la izquierda, un archivo style.css conectado al HTML con la línea de abajo; a la derecha, JSFiddle con el panel CSS resaltado. Texto en pantalla: «En JSFiddle, el panel CSS ya está conectado».

```html
<link rel="stylesheet" href="style.css">
```

> En una página normal, el CSS se guarda en un archivo aparte y se conecta con una etiqueta link dentro del head, que le dice al navegador: «busca los estilos en este archivo». Es como llevar la ropa en un cajón separado del esqueleto. En JSFiddle todo es más fácil: el panel CSS se aplica a tu HTML al ejecutar el ejemplo: escribe los estilos y pulsa Run.

### Escena 4 · Demostración: colores y fuentes 
**En pantalla**: JSFiddle con la página del Ejercicio 4. Se escriben las reglas una por una y pulsamos Run para actualizar el resultado. Texto en pantalla para cada propiedad nueva: color, background-color, font-family, font-size.

```css
body {
  background-color: #f0f8ff;
  font-family: Arial, sans-serif;
}

h1 {
  color: darkblue;
  font-size: 40px;
}

p {
  color: #333333;
  font-size: 18px;
}
```

> Vamos al panel CSS. Empiezo con el selector body, que representa toda la página. Con background-color cambio el color de fondo. Los colores se pueden escribir con su nombre en inglés, como blue o darkblue, o con un código que empieza con numeral, llamado código hexadecimal. No tienes que memorizarlos: en internet hay selectores de color para copiarlos. Ahora la propiedad font-family cambia el tipo de letra. Pongo Arial, y después sans-serif como alternativa por si el dispositivo no tiene esa letra. Sigo con h1: le cambio el color y con font-size el tamaño, que se mide en píxeles. Y ahora los párrafos: un gris oscuro, porque el negro puro puede cansar la vista, y un tamaño de 18 píxeles para que se lea mejor. ¡Mira cuánto cambió con solo tres reglas!

### Escena 5 · Selectores de clase 

**En pantalla**: dos párrafos en el HTML: uno normal y otro con el atributo `class="destacado"`. Se escribe la regla `.destacado` y solo el segundo párrafo cambia. Texto en pantalla: «Clase: usa un punto en CSS».

```html
<p>Un párrafo normal.</p>
<p class="destacado">Un párrafo especial.</p>
```

```css
.destacado {
  color: crimson;
  font-weight: bold;
}
```

> Hasta ahora todos los párrafos se ven igual. ¿Y si quiero que solo uno sea diferente? Para eso usamos las clases. Una clase es un nombre que tú inventas y colocas en un elemento con el atributo class. Aquí le puse destacado al segundo párrafo. En el CSS, para elegir una clase, escribo un punto y el nombre: punto destacado. Esa regla solo afecta a los elementos que tengan esa clase. Mira: el primer párrafo no cambió, el segundo sí. Con font-weight bold lo puse en negrita. Las clases son una de las herramientas más usadas en CSS.

### Escena 6 · Práctica y cierre 

**En pantalla**: JSFiddle con HTML y CSS visibles. Cambiar background-color, color de h1 y font-family; ejecutar tras cada cambio. Añadir `class="destacado"` a un párrafo y la regla `.destacado` en CSS. Cierre: «Pausa y prueba: personaliza tres estilos».

> «Vamos a vestir nuestra página. En CSS escribo `body { background-color: #f0f8ff; font-family: Arial, sans-serif; }`. Pulso Run: cambia el fondo y la letra. Después escribo `h1 { color: darkblue; }` y ejecuto: solo cambia el título principal. Ahora quiero destacar una frase. En HTML agrego `class="destacado"` a un párrafo y en CSS escribo `.destacado { color: crimson; font-weight: bold; }`. El punto significa que estamos buscando una clase. Ejecutamos y solo ese párrafo se resalta. Ahora pausa: elige otro color de fondo, otro color para el título y una frase especial. Comprueba con Run qué regla cambia cada parte».

---

## Video 6 · Centrar, colores y bordes 

**Objetivo**: centrar texto y bloques, y usar bordes, bordes redondeados y espacios (padding y margin) para crear una tarjeta.

**Enlace en la descripción**: JSFiddle del Ejercicio 6 (Mi tarjeta).

### Escena 1 · Repaso y objetivo 
**En pantalla**: el resultado final: una tarjeta centrada con borde redondeado y fondo de color.

> Bienvenido de nuevo. Hoy vas a lograr algo que se ve en casi todas las páginas: una tarjeta centrada, con bordes redondeados y colores. Para eso aprenderás a centrar, a poner bordes y a controlar los espacios.

### Escena 2 · Centrar texto 

**En pantalla**: JSFiddle. Se escribe la regla y el título se mueve al centro.

```css
h1 {
  text-align: center;
}
```

> Centrar texto es muy fácil: usamos la propiedad text-align con el valor center. Se aplica al elemento que contiene el texto. También puedes usar left, para la izquierda, o right, para la derecha. Mira cómo el título se movió al centro.

### Escena 3 · Los espacios: la caja de cada elemento 

**En pantalla**: diagrama de una caja con cuatro capas rotuladas, de adentro hacia afuera: «contenido», «padding (espacio interno)», «border (borde)» y «margin (espacio externo)». Analogía visual: un cuadro colgado en la pared (la foto, el marco y el espacio libre hasta el siguiente cuadro).

> En CSS, todo elemento es una caja. Dentro está el contenido. Alrededor, el padding, que es el espacio entre el contenido y el borde, como el papel que rodea la foto en un cuadro. Después viene el borde, que es el marco. Y por fuera, el margin, que es la distancia entre ese elemento y los que lo rodean. Si lo piensas como un cuadro en la pared: la foto es el contenido, el espacio interior es el padding, el marco es el borde y el espacio hasta el siguiente cuadro es el margin. Con esta idea de la caja entenderás por qué las cosas se mueven o se pegan.

### Escena 4 · Demostración: construye la tarjeta 

**En pantalla**: JSFiddle. En el HTML hay un div con la clase tarjeta que contiene un h2 y un párrafo. Se escribe el CSS paso a paso, y después de cada propiedad nueva se pulsa Run para actualizar el resultado. Texto en pantalla para cada propiedad: width, padding, border, border-radius, margin.

```html
<div class="tarjeta">
  <h2>Mi tarjeta</h2>
  <p>Aprendiendo a dar estilo con CSS.</p>
</div>
```

```css
.tarjeta {
  max-width: 300px;
  padding: 20px;
  border: 3px solid darkblue;
  border-radius: 15px;
  background-color: lightyellow;
  text-align: center;
  margin: 0 auto;
}
```

> Aquí tengo un elemento div. Un div es una caja sin significado especial, que sirve para agrupar otros elementos. Le puse la clase tarjeta. Voy a darle estilo. Primero, max-width de 300 píxeles: la tarjeta no será más ancha que eso. Luego padding de 20 píxeles, para que el texto no quede pegado al borde. Ahora el borde: la propiedad border lleva tres datos juntos, el grosor, el tipo de línea, que puede ser solid, dashed o dotted, y el color. Con border-radius redondeo las esquinas: mientras mayor el número, más redonda. Agrego un fondo amarillo claro y centro el texto. Y falta lo más importante: centrar la tarjeta en la página. Para eso uso margin con dos valores: cero y auto. El cero es para arriba y abajo; auto le dice al navegador que reparta el espacio sobrante a izquierda y derecha, y por eso la tarjeta queda centrada. Recuerda que esto funciona porque la tarjeta tiene un ancho máximo definido.

### Escena 5 · Prueba y juega 

**En pantalla**: se cambian valores en vivo: el color del borde, el radio, el padding.

> Ahora juega un poco. Si cambio el radio a 50 píxeles, la tarjeta se ve casi como una píldora. Si cambio el padding, el texto se acerca o se aleja del borde. Experimentar es la mejor manera de aprender CSS.

### Escena 6 · Práctica y cierre

**En pantalla**: crear en JSFiddle una tarjeta con div, h2 y p; aplicar CSS por etapas: ancho, padding, border, border-radius y margin. Ejecutar y comparar. Cierre: «Pausa y prueba: tu propia tarjeta».

> «Primero agrupamos el título y el párrafo dentro de `<div class="tarjeta">`. En CSS escribimos `.tarjeta { max-width: 300px; }` para limitar su ancho. Agrego `padding: 20px;` y el texto se separa del borde. Ahora `border: 3px solid darkblue;` dibuja el marco, y `border-radius: 15px;` redondea las esquinas. Con `background-color: lightyellow;` aparece el fondo. Finalmente, `margin: 0 auto;` centra la caja horizontalmente cuando hay espacio disponible. Pulso Run después de cada cambio para comparar. Ahora pausa: cambia el título por tu apodo, el párrafo por tu pasatiempo y prueba otro color de borde. ¿Qué pasa si aumentas border-radius?».

---

## Video 7 · Construye tu página de perfil 

**Objetivo**: combinar HTML y CSS para crear una página de perfil personal completa, paso a paso, usando solo datos ficticios o apodos.

**Enlace en la descripción**: JSFiddle del Ejercicio 7 (Mi perfil), con el HTML base.

### Escena 1 · Presentación del proyecto 

**En pantalla**: el resultado final (la página de perfil terminada) y debajo un boceto en papel con las secciones numeradas: 1) foto, 2) título, 3) sobre mí, 4) mis gustos, 5) mi enlace favorito.

> ¡Llegó el gran momento! Hoy vas a crear tu propia página de perfil, usando todo lo que aprendiste. Mira cómo queda al final. Antes de escribir código, un truco de los profesionales: primero se dibuja un boceto. Yo dibujé el mío en papel: arriba una imagen, luego el título con mi apodo, una sección «Sobre mí», una lista con mis gustos y un enlace a una página que me encanta. Y una regla importante: en tu perfil usa un apodo y gustos generales. No escribas tu nombre completo, tu colegio, tu dirección, tu teléfono ni subas fotos tuyas. Cuida tu privacidad.

### Escena 2 · Paso 1: el contenido en HTML 

**En pantalla**: JSFiddle. Se escribe el HTML por bloques; se resalta cada uno con el número del boceto. Texto en pantalla: «Primero el contenido (HTML), después el estilo (CSS)».

```html
<div class="perfil">
  <img src="https://picsum.photos/id/237/200/200" alt="Imagen de perfil" width="150">
  <h1>Alex</h1>
  <p class="lema">Aprendiendo a crear páginas web</p>

  <h2>Sobre mí</h2>
  <p>Me gusta jugar <strong>fútbol</strong> y dibujar. Estoy aprendiendo HTML y CSS.</p>

  <h2>Mis gustos</h2>
  <ul>
    <li>Videojuegos</li>
    <li>Música</li>
    <li>Dibujar</li>
  </ul>

  <h2>Mi sitio favorito</h2>
  <p><a href="https://developer.mozilla.org/es/" target="_blank">Aprender más en MDN</a></p>
</div>
```

> Empezamos con el contenido, sin pensar en colores todavía. Primero un div con la clase perfil, que será la caja que agrupa todo. Dentro va la imagen, con su atributo alt, y un h1 con mi apodo: Alex. Debajo, un párrafo con un lema. Luego un h2 «Sobre mí» y un párrafo donde destaco una palabra con strong. Sigue un h2 «Mis gustos» con una lista de tres elementos. Y termino con un enlace a una página que me gusta. Fíjate que usé cada elemento que aprendimos: encabezados, párrafos, lista, imagen y enlace. Ahora el resultado se ve ordenado, pero muy simple. Pausa si necesitas copiar o escribir con calma; después seguimos con el estilo.

### Escena 3 · Paso 2: el estilo en CSS 

**En pantalla**: JSFiddle, panel CSS. Se escribe el código por bloques y se pulsa Run después de cada bloque para ver cómo se transforma el resultado. Texto en pantalla con el nombre de cada bloque: «Fondo y letra», «Caja del perfil», «Títulos», «Imagen redonda», «Lista y enlace».

```css
body {
  background-color: #e8f0fe;
  font-family: Arial, sans-serif;
}

.perfil {
  max-width: 400px;
  margin: 30px auto;
  padding: 25px;
  background-color: white;
  border: 3px solid #4a6fa5;
  border-radius: 20px;
  text-align: center;
}

h1 {
  color: #4a6fa5;
}

h2 {
  color: #333333;
  font-size: 20px;
}

.lema {
  font-style: italic;
  color: #666666;
}

img {
  border-radius: 50%;
}

ul {
  text-align: left;
  display: inline-block;
}

a {
  color: #4a6fa5;
  font-weight: bold;
}
```

> Ahora el estilo. Primero el body: un fondo azul muy claro y la letra Arial. Luego la caja del perfil: ancho máximo de 400 píxeles, margin de 30 píxeles arriba y abajo y auto a los lados para centrarla, padding para que respire, fondo blanco, borde azul con esquinas redondeadas y texto centrado. Mira cómo ya parece una tarjeta de verdad. Sigo con los títulos: el h1 en azul y los h2 en gris oscuro con un tamaño menor. Al lema le doy cursiva y un gris suave. Y ahora un truco: a la imagen le pongo border-radius de 50 por ciento, y se convierte en un círculo. Para la lista, la alineo a la izquierda y con display inline-block hago que la lista ocupe solo el ancho que necesita; así queda centrada en la tarjeta, pero con los textos alineados. Por último, el enlace en azul y negrita. ¡Y listo!

### Escena 4 · Paso 3: personaliza 

**En pantalla**: se modifican los valores y se pulsa Run para ver los cambios el nombre, los colores y los gustos de la página.

> Ahora hazla tuya. Cambia el apodo, los gustos, el color de fondo y los colores de los títulos. Puedes cambiar la imagen por otra de licencia libre o por un dibujo tuyo. Recuerda mantener buen contraste: letras oscuras sobre fondos claros o al revés, para que todo se lea bien.

### Escena 5 · Depurar errores 

**En pantalla**: una lista de comprobación animada.

> Si algo no funciona, revisa esta lista. Uno: ¿cerraste todas las etiquetas? Dos: ¿cada regla de CSS tiene sus llaves y sus puntos y coma? Tres: ¿el nombre de la clase es igual en el HTML y en el CSS? Y cuatro: ¿la imagen tiene bien su dirección? Casi siempre el problema es una de estas cuatro.

### Escena 6 · Práctica y cierre 

**En pantalla**: repasar el perfil construido en JSFiddle, cambiar apodo, gustos y colores en directo, ejecutar y mostrar cómo compartir el resultado según las opciones disponibles. Cierre: «Pausa y personaliza tu perfil».

> «Ya tenemos la estructura y el estilo de nuestro perfil. Antes de terminar, vamos a personalizarlo. En HTML cambio “Alex” por un apodo inventado y sustituyo los tres gustos de la lista. Pulso Run para revisar el contenido. Ahora en CSS cambio background-color para elegir otro fondo y modifico el color del h1. Ejecuto otra vez: es la misma página, pero ahora tiene un estilo diferente. Pausa el video y haz estos cambios en tu versión. Comprueba que la imagen tenga alt, que el enlace funcione y que no hayas incluido datos personales. Si quieres compartir tu trabajo, utiliza la opción de guardar o compartir de JSFiddle cuando esté disponible; puede requerir iniciar sesión».

---

## Video 8 · Errores comunes y próximos pasos 

**Objetivo**: reconocer los errores más frecuentes de quienes empiezan, conocer herramientas para validar el código y saber cómo seguir aprendiendo.

**Enlace en la descripción**: JSFiddle del Ejercicio 8 (Encuentra los errores), validador de HTML de W3C, documentación de MDN y cuestionario final.

### Escena 1 · Bienvenida y objetivo

**En pantalla**: captura de la página de perfil del video anterior.

> ¡Lo lograste! Ya creaste una página web. En este último video repasamos los errores más comunes de quienes empiezan, cómo corregirlos y qué puedes aprender después.

### Escena 2 · Los cinco errores más comunes

**En pantalla**: una tarjeta por error; en cada una, el código incorrecto en rojo y el correcto en verde. Íconos de aviso. Se muestran los cinco errores con ejemplos cortos.

> Error número uno: olvidar cerrar una etiqueta. Si abres un p y no lo cierras, la página se desordena. Error número dos: olvidar las comillas en los atributos, como en src o href. Error número tres: en CSS, olvidar el punto y coma al final de una línea o una llave de cierre. Error número cuatro: escribir mal el nombre de una clase; si en el HTML dice destacado y en el CSS escribes destacada, no funcionará. Y error número cinco: olvidar el texto alternativo en las imágenes o usar un h1 solo por su tamaño. Cometer errores es normal; todos los programadores los cometen todos los días. Lo importante es saber buscarlos.

### Escena 3 · Cómo encontrar errores 

**En pantalla**: grabación de pantalla de la página validadora de HTML de W3C pegando un fragmento con un error; muestra el mensaje. Luego, la página de MDN Web Docs.

> Hay herramientas que te ayudan. Una es el validador de HTML del W3C: pegas tu código y te dice dónde hay errores. Otra es MDN Web Docs, una gran documentación gratuita, en español, donde puedes buscar cualquier etiqueta o propiedad. Y hay un hábito muy útil: escribe poco código a la vez y revisa el resultado después de cada cambio. También usa la sangría para que tu código se lea mejor, y los comentarios para dejarte notas.

### Escena 4 · Próximos pasos 

**En pantalla**: ruta de aprendizaje con cuatro paradas: «Practica», «CSS más avanzado», «JavaScript», «Tu propio proyecto».

> ¿Y ahora qué? Primero, practica: crea otra página sobre un tema que te apasione. Después, aprende más CSS, por ejemplo cómo organizar elementos en columnas. Luego, JavaScript, para que tu página reaccione cuando alguien hace clic. Y finalmente, crea tu propio proyecto: un blog, un portafolio o un sitio para tu club favorito.

### Escena 5 · Cierre 

**En pantalla**: mostrar en JSFiddle el código con errores del Ejercicio 8. Corregir en directo cierre de h1, comillas de src, alt, nombre de clase y punto y coma; ejecutar antes y después. Cierre: «Pausa y encuentra un error por tu cuenta».

> «Para terminar, abrimos en JSFiddle una página con algunos errores. Primero reviso el título: falta `</h1>`, así que lo agrego. Luego veo la imagen: pongo entre comillas la dirección de src y añado alt para describirla. Después comparo el nombre de la clase en HTML y CSS: ambos deben decir destacado. Por último, agrego el punto y coma que falta después de color: red. Pulso Run y compruebo el resultado. Ahora pausa: vuelve al código inicial y trata de corregirlo tú sin mirar la solución. Después responde el cuestionario final. ¡Ya sabes crear, probar y mejorar una página con HTML y CSS!».

---

## 3. Sección de ejercicios

Cada ejercicio se muestra al final de su video con la pantalla «Pausa el video». Para cada uno hay un **código inicial** (lo que se precarga en el editor en línea y va en `/starter-files`) y una **solución** (va en `/completed-examples`). Duración sugerida de cada ejercicio: de 3 a 5 minutos, salvo el Ejercicio 7, que puede tomar entre 10 y 15 minutos.

### Ejercicio 1 · Explorar un sitio web (Video 1)

**Meta**: distinguir el contenido (HTML) del estilo (CSS).

**Instrucciones**:

1. Abre el enlace del editor. Verás una página sencilla.
2. Cambia el texto del título por tu propia frase.
3. En el panel CSS, cambia lightblue por otro color.
4. Responde: ¿qué panel cambió el texto y cuál cambió el color?

**Código inicial (HTML)**:

```html
<h1>Bienvenido a mi página</h1>
<p>Esta página tiene contenido (HTML) y estilo (CSS).</p>
```

**Código inicial (CSS)**:

```css
body {
  background-color: lightblue;
  font-family: Arial, sans-serif;
}

h1 {
  color: purple;
}
```

**Respuesta**: el texto lo cambia el HTML; el color lo cambia el CSS.

---

### Ejercicio 2 · Mi primera página (Video 2)

**Meta**: escribir elementos con etiqueta de apertura, contenido y etiqueta de cierre.

**Instrucciones**:

1. Escribe un `<h1>` con tu apodo.
2. Escribe dos párrafos con `<p>` sobre lo que te gusta hacer.
3. Borra a propósito una etiqueta de cierre y observa qué pasa. Luego corrígela.

**Código inicial**: panel HTML vacío con un comentario: `<!-- Escribe aquí tu primera página -->`

**Solución**:

```html
<h1>Alex</h1>
<p>Me gusta jugar fútbol con mis amigos.</p>
<p>Estoy aprendiendo a crear páginas web.</p>
```

---

### Ejercicio 3 · Mi pasatiempo favorito (Video 3)

**Meta**: usar encabezados, párrafos, texto resaltado y listas.

**Instrucciones**: crea una página con un `<h1>`, dos `<h2>` y un párrafo bajo cada uno. Resalta una palabra con `<strong>` y agrega una lista de tres elementos. Reto: cambia la lista a una lista ordenada.

**Código inicial**:

```html
<h1>Mi pasatiempo favorito</h1>
<!-- Agrega un h2, un párrafo y una lista -->
```

**Solución**:

```html
<h1>Mi pasatiempo favorito</h1>

<h2>¿Por qué me gusta?</h2>
<p>Me gusta <strong>mucho</strong> dibujar porque puedo inventar lo que quiera.</p>

<h2>Mis tres razones</h2>
<ul>
  <li>Me divierte</li>
  <li>Me relaja</li>
  <li>Lo hago con mis amigos</li>
</ul>
```

---

### Ejercicio 4 · Imagen y enlace (Video 4)

**Meta**: insertar una imagen con texto alternativo y crear un enlace.

**Instrucciones**: agrega a la página del Ejercicio 3 una imagen con src, alt y width, y un enlace que se abra en una pestaña nueva. Verifica que el texto del enlace diga a dónde lleva.

**Código inicial**: la solución del Ejercicio 3.

**Solución (parte nueva)**:

```html
<img src="https://picsum.photos/id/10/400/250" alt="Bosque junto a un lago" width="300">

<p>
  <a href="https://developer.mozilla.org/es/" target="_blank">Aprende más en MDN</a>
</p>
```

---

### Ejercicio 5 · Estilo a mi página (Video 5)

**Meta**: escribir reglas CSS con selectores de elemento y de clase.

**Instrucciones**:

1. Cambia el fondo de la página y el tipo de letra.
2. Cambia el color de los títulos h1 y h2.
3. Crea la clase destacado, aplícala a una frase y dale un color y negrita.

**Código inicial**: la página del Ejercicio 4 con el panel CSS vacío.

**Solución (CSS)**:

```css
body {
  background-color: #f0f8ff;
  font-family: Arial, sans-serif;
}

h1 {
  color: darkblue;
}

h2 {
  color: teal;
}

.destacado {
  color: crimson;
  font-weight: bold;
}
```

En el HTML, la frase queda así: `<p class="destacado">¡Esta es mi frase favorita!</p>`

---

### Ejercicio 6 · Mi tarjeta (Video 6)

**Meta**: centrar una tarjeta con borde redondeado, relleno y fondo de color.

**Instrucciones**: crea una tarjeta con tu apodo y tu pasatiempo favorito. Debe estar centrada, con borde redondeado y color de fondo. Reto: haz que el borde sea de línea punteada (dotted).

**Código inicial (HTML)**:

```html
<div class="tarjeta">
  <h2>Mi tarjeta</h2>
  <p>Escribe aquí tu pasatiempo.</p>
</div>
```

**Solución (CSS)**:

```css
.tarjeta {
  max-width: 300px;
  margin: 40px auto;
  padding: 20px;
  border: 3px solid darkgreen;
  border-radius: 15px;
  background-color: honeydew;
  text-align: center;
}
```

---

### Ejercicio 7 · Mi página de perfil, proyecto final (Video 7)

**Meta**: combinar todo lo aprendido en una página de perfil personal.

**Instrucciones**:

1. Dibuja un boceto en papel con las secciones de tu perfil.
2. Escribe el HTML con el apodo, la imagen, «Sobre mí», una lista de gustos y un enlace.
3. Agrega el CSS: fondo, tarjeta centrada, bordes, colores y una imagen redonda.
4. Personalízala y guarda el enlace de tu JSFiddle.

**Reglas de seguridad**: usa un apodo, gustos generales y no publiques datos personales ni fotos tuyas.

**Código inicial**: panel HTML y CSS vacíos con la estructura del boceto como comentarios.

**Solución**: el código completo del Video 7 (HTML y CSS). Guardarlo en `/completed-examples/perfil/`.

**Lista de comprobación para el estudiante**:

- Hay un solo `<h1>` y los encabezados siguen un orden lógico.
- La imagen tiene su atributo `alt`.
- El enlace tiene un texto que explica a dónde lleva.
- Todas las etiquetas están cerradas y cada regla de CSS termina con punto y coma.
- No aparece ningún dato personal.

---

### Ejercicio 8 · Encuentra los errores (Video 8)

**Meta**: reconocer y corregir los errores más frecuentes.

**Instrucciones**: el siguiente código tiene 5 errores (4 en el HTML y 1 en el CSS, más un cambio de nombre de clase). Encuéntralos y corrígelos hasta que la página se vea bien.

**Código inicial (HTML)**:

```html
<h1>Mi página
<p>Me gusta la música.</p>
<img src=https://picsum.photos/id/10/200/150>
<p class="destacado">Esta es una frase importante</p>
```

**Código inicial (CSS)**:

```css
.destacada {
  color: red
  font-size: 20px;
}
```

**Errores**:

1. El `<h1>` no tiene etiqueta de cierre.
2. El valor del atributo `src` no está entre comillas.
3. La imagen no tiene el atributo `alt`.
4. La clase se llama `destacado` en el HTML y `destacada` en el CSS.
5. Falta el punto y coma después de `red`.

**Solución**:

```html
<h1>Mi página</h1>
<p>Me gusta la música.</p>
<img src="https://picsum.photos/id/10/200/150" alt="Bosque junto a un lago">
<p class="destacado">Esta es una frase importante</p>
```

```css
.destacado {
  color: red;
  font-size: 20px;
}
```

---

## 4. Material para el repositorio y verificaciones finales

La estructura pedida en el enunciado puede quedar así:

| Carpeta | Contenido |
|---------|-----------|
| `/starter-files` | Códigos iniciales de los ejercicios 1 a 8 (un archivo HTML y uno CSS por ejercicio) |
| `/completed-examples` | Soluciones de los ejercicios 1 a 8 y el perfil completo del Video 7 |
| `/scripts` | Los guiones de este documento, un archivo .md por video |

**Antes de grabar, verifiquen lo siguiente**:

- **Editor en línea**: que cada enlace de JSFiddle abra sin iniciar sesión y permita editar. Si alguno pide cuenta, usen JSFiddle para ese ejercicio.
- **Esqueleto en JSFiddle**: que el panel HTML funcione como body, tal como se explica en los videos 2 y 5.
- **Imágenes**: que la imagen usada en los ejemplos coincida con su texto alt; si prefieren, sustitúyanla por una imagen propia en `/starter-files`.
- **Enlaces de ejemplo**: que los enlaces externos (MDN, validador de W3C) sigan activos.
- **Videos**: que el audio sea claro, que el texto del editor se lea en pantalla completa y que cada video esté como no listado con los enlaces en la descripción.
- **Documento Markdown**: que enlace los 8 videos, el repositorio y los editores de cada práctica, y que incluya la sección «Elaboración» de la plantilla del Anexo A.
