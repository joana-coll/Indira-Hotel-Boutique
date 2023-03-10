<!-- T脥TULO Y DESCRIPCI脫N -->
  <a name="ir-arriba"></a>
  # 馃捇 Encuesta de satisfacci贸n de Indira Hotel Boutique

  Proyecto N掳1 para la certificaci贸n de Dise帽o Web Adaptativo correspondiente a **freeCodeCamp**
  <div align="center">
    <table>
      <tr>
        <td>
          <p>Consigna: Construye un formulario en HTML y CSS</p>
          <p>Objetivo: Crea una aplicaci贸n que sea funcionalmente similar a https://survey-form.freecodecamp.rocks</p>
        </td>
        <td>
          <img src="https://github.com/jc-projects/freeCodeCamp_Encuesta/blob/main/img/imgREADME.gif" width="400px">
        </td>
      </tr>
    </table>
  </div>

<!-- 脥NDICE -->
  <a name="indice"></a>
  ## 馃搶 脥ndice
  <ol>
    <li><a href="#ir-arriba">T铆tulo y descripci贸n del proyecto</a></li>
    <li><a href="#indice">脥ndice</a></li>
    <li><a href="#tecnologias">Tecnolog铆as utilizadas</a></li>
    <li><a href="#instalacion">Instalaci贸n</a></li>
    <li><a href="#historias-de-usuario">Historias de usuario</a></li>
    <li><a href="#pruebas">Pruebas</a></li>
    <li><a href="#desarrollado">Desarrollado por...</a>
    <li><a href="#contacto">Contacto</a>
    <li><a href="#agradecimiento">Agradecimiento</a>
  </ol>

<!-- TECNOLOG脥AS UTILIZADAS -->
  <a name="tecnologias"></a>
  ## 鉁? Tecnolog铆as utilizadas
  <p align="center">
    <a href="https://en.wikipedia.org/wiki/HTML5" target="_blank">
      <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white">
    </a>
    <a href="https://www.w3schools.com/css/" target="_blank">
      <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white">
    </a>
    <a href="https://www.netlify.com" target="_blank">
      <img src="https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7">
    </a>
   </p>
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>

<!-- INSTALACI脫N -->
  <a name="instalacion"></a>
  ## 馃敡 Instalaci贸n
  Si deseas correr la web en un entorno local debes tener en cuenta lo siguiente: 
  1. Clona el repositorio utilizando GIT o descargando el archivo ZIP:

      `git clone https://github.com/joana-coll/Indira-Hotel-Boutique.git`
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>
  
<!-- HISTORIAS DE USUARIO -->
  <a name="historias-de-usuario"></a>
  ## 馃殌 Historias de usuario
  1. Debes tener un t铆tulo de p谩gina en un elemento `h1` con un `id` de `title`
  2. Debes tener una corta explicaci贸n en el elemento `p` con un `id` de `description`
  3. Debes tener un elemento `form` con un `id` de `survey-form`
  4. Dentro del elemento form, debe ser <b>required</b> (requerido) ingresar tu nombre en un campo de `input` que tenga un `id` de `name` y un `type` de `text`
  5. Dentro del elemento form <b>required</b> (requerido) ingresar tu nombre en un campo de `input` que tenga un `id` de `email`
  6. Si ingresas un email que no tenga el formato correcto, ver谩s un error de validaci贸n HTML5
  7. Dentro del formulario, puedes ingresar un n煤mero en un campo de `input` que tenga un `id` de `number`
  8. La entrada de n煤meros no debe aceptar caracteres no num茅ricos, ya sea impidiendo que los escribas o mostrando un error de validaci贸n HTML5 (dependiendo del navegador)
  9. Si ingrisas un n煤mero que est茅 fuera del rango de n煤meros permitido, que es definido por los atributos `min` y `max`, ver谩s un error de validaci贸n de HTML5
  10. Para los campos de entrada de nombre, email y n煤mero, puedes ver los correspondientes elementos `label` en el formulario, que describen el prop贸sito de cada campo con los siguientes id: `id="name-label"`, `id="email-label"` y `id="number-label"`
  11. Para los campos de entrada de nombre, email y n煤mero, podr谩s ver un texto provisional que da una descripci贸n o instrucciones para cada campo
  12. Dentro del elemento form, debes tener un elemento desplegable `select` con un `id` de `dropdown` con al menos dos opciones para elegir
  13. Dentro del elemento form, puedes seleccionar una opci贸n de un grupo de al menos dos botones de radio que son agrupado utilizando el atributo `name`
  14. Dentro del elemento form, puedes seleccionar varios campos en una serie de casillas de verificaci贸n, cada una debe tener un atributo `value`
  15. Dentro del elemento form, se te presenta un `textarea` para comentarios adicionales
  16. Dentro del elemento form, se te presenta un bot贸n con un `id` de `submit` para enviar todas las entradas
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>
  
<!-- PRUEBAS -->
  <a name="pruebas"></a>
  ## 鈿欙笍 Pruebas
  <ul>
    <li>Debes tener un elemento <b>h1</b> con un <b>id</b> de <b>title</b></li>
    <li>Tu <b>#title</b> no debe estar vac铆o.</li>
    <li>Debes tener un elemento <b>p</b> con un <b>id</b> de <b>description</b></li>
    <li>Tu <b>#description</b> no debe estar vac铆o</li>
    <li>Debes tener un elemento <b>form</b> con un <b>id</b> de <b>survey-form</b></li>
    <li>Debes tener un elemento <b>input</b> con un <b>id</b> de <b>name</b></li>
    <li>Tu <b>#name</b> debe tener un <b>type</b> de <b>text</b></li>
    <li>Tu <b>#name</b> debe requerir una entrada</li>
    <li>Tu <b>#name</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Debes tener un elemento <b>input</b> con un <b>id</b> de <b>email</b></li>
    <li>Tu <b>#email</b> debe tener un <b>type</b> de <b>email</b></li>
    <li>Tu <b>#email</b> debe requerir una entrada</li>
    <li>T煤 <b>#email</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Debes tener un elemento <b>input</b> con un <b>id</b> de <b>number</b></li>
    <li>Tu <b>#number</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Tu <b>#number</b> debe tener un <b>type</b> de <b>number</b></li>
    <li>Tu <b>#number</b> debe tener un atributo <b>min</b> con un valor num茅rico</li>
    <li>Tu <b>#number</b> debe tener un atributo <b>max</b> con un valor num茅rico</li>
    <li>Debes tener un elemento <b>label</b> con un <b>id</b> de <b>name-label</b></li>
    <li>Debes tener un elemento <b>label</b> con un <b>id</b> de <b>email-label</b></li>
    <li>Debes tener un elemento <b>label</b> con un <b>id</b> de <b>number-label</b></li>
    <li>Tu <b>#name-label</b> debe contener un texto que describa la entrada</li>
    <li>Tu <b>#email-label</b> debe contener un texto que describa la entrada</li>
    <li>Tu <b>#number-label</b> debe contener un texto que describa la entrada</li>
    <li>Tu <b>#name-label</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Tu <b>#email-label</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Tu <b>#number-label</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Tu <b>#name</b> debe tener el atributo <b>placeholder</b> y un valor</li>
    <li>Tu <b>#email</b> debe tener un atributo <b>placeholder</b> y un valor</li>
    <li>Tu <b>#number</b> debe tener un atributo <b>placeholder</b> y un valor</li>
    <li>Debes tener un campo <b>select</b> con un <b>id</b> de <b>dropdown</b></li>
    <li>Tu <b>#dropdown</b> debe tener al menos dos elementos <b>option</b> seleccionables (no deshabilitados)</li>
    <li>Tu <b>#dropdown</b> debe ser descendiente de <b>#survey-form</b></li>
    <li>Debes tener al menos dos elementos <b>input</b> con un <b>type</b> de <b>radio</b> (botones de radio)</li>
    <li>Debes tener al menos dos botones de radio que sean descendientes de <b>#survey-form</b></li>
    <li>Todos tus botones de radio deben tener un atributo <b>value</b> y un valor</li>
    <li>Todos tus botones de radio deben tener un atributo <b>name</b> y un valor</li>
    <li>Cada grupo de bot贸n de radio debe tener al menos 2 botones de radio</li>
    <li>Debes tener al menos dos elementos <b>input</b> con un <b>type</b> de <b>checkbox</b> (casillas de verificaci贸n) que sean descendientes de <b>#survey-form</b></li>
    <li>Todos tus casillas de verificaci贸n dentro de <b>#survey-form</b> deben tener un atributo <b>value</b> y un valor</li>
    <li>Debes tener al menos un elemento de <b>textarea</b> que sea descendiente de <b>#survey-form</b></li>
    <li>Debes tener un elemento <b>input</b> o <b>button</b> con un <b>id</b> de <b>submit</b></li>
    <li>Tu <b>#submit</b> debe tener un <b>type</b> de <b>submit</b></li>
    <li>Tu <b>#submit</b> debe ser descendiente de <b>#survey-form</b></li>   
  </ul>
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>
  
<!-- DESARROLLADO POR -->
  <a name="desarrollado"></a>
  ## 馃拋 Desarrollado por...
  * **Joana Coll** - [joana-coll](https://github.com/joana-coll)
  
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>
  
<!-- CONTACTO -->
  <a name="contacto"></a>
  ## 馃摡 Contacto
  Si deseas contactarte conmigo:
  <a href="https://ar.linkedin.com/in/joana-coll" target="_blank">
  <img src="https://raw.githubusercontent.com/joana-coll/joana-coll/1ce466f12c925e1e39ab93b44ff985f102c9aed8/icons/linkedin.svg" alt="Github" height="30" />
  </a>
  <a href="mailto:colljoana@gmail.com" target="_blank">
  <img src="https://raw.githubusercontent.com/joana-coll/joana-coll/1ce466f12c925e1e39ab93b44ff985f102c9aed8/icons/envelope-solid.svg" alt="Github" height="30" />
  </a>
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>

<!-- AGRADECIMIENTO -->
  <a name="agradecimiento"></a>
  ## 鉂わ笍 Agradecimiento
  Gracias por leer hasta aqu铆, espero que el proyecto te sea 煤til. No tiene Licencia pero podes usarlo como gustes mientras sigas fomentando el c贸digo libre y ayudando a otros pares. 
  
  隆Que tengas un lindo d铆a!
  
  Nana 鉁?
  <p align="right">(<a href="#ir-arriba">Ir arriba</a>)</p>
  
