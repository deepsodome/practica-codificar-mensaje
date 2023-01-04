<div align="center">

  <img src="https://parasmarthome.online/encriptador/images/preview01.jpg" alt="logo" width="940" height="auto" />
  <h1>Encriptado de mensjaes y enviar por App</h1>
  
  <p>
    Es una aplicación de práctica que se solicito para el programa de Oracle ONE. Esta aplicación tiene como propósito de encriptar y desencriptar un texto cambiendo letras especficas por otro texto.
  Dando como resultado una texto incomprensible para cualquier usuario. 
  </p>
  <br />
<h1>Visitar página</h1>
<button onclick="location.href='http://www.example.com'" type="button"><h2>
         https://deepsodome.github.io/codificar-mensaje/</h2></button>

<br />
  </div>
  
<br />

<!-- Tabla de contenido -->
# :notebook_with_decorative_cover: Tabla de contenido

- [Proyecto](#:star:-Proyecto)
  * [Capturas](#-Capturas)
  * [Funciones](#-Funciones)
  * [Validaciones](#-Validaciones)
  * [Funcionamiento](#-Flujo-de-usuario)
  * [Mensaje WhatsApp](#-mensaje-whatsapp)
  
<br />
  
<!-- Proyecto -->
## boockmark_tabs Proyecto


<!-- Capturas -->
### :framed_picture: Capturas

<div>
  <div align="center"> 
    <h2>Escritorio</h2>
    <img src="https://parasmarthome.online/capturas/escritorio1.jpg" alt="screenshot" />
  </div>
  <div align="center"> 
    <img src="https://parasmarthome.online/capturas/escritorio2.jpg" alt="screenshot" />
  </div>
  <div align="center"> 
    <img src="https://parasmarthome.online/capturas/escritorio3.jpg" alt="screenshot" />
  </div>
</div>

<div>
  <div align="center">
    <h2>Tablet</h2>
    <img src="https://parasmarthome.online/capturas/tablet1.jpg" alt="screenshot" />
  </div>
  <div align="center"> 
    <img src="https://parasmarthome.online/capturas/tablet2.jpg" alt="screenshot" />
  </div>
  <div align="center"> 
    <img src="https://parasmarthome.online/capturas/tablet3.jpg" alt="screenshot" />
  </div>
</div>

<div>
  <div align="center"> 
    <h2>Smatphone</h2>
    <img src="https://parasmarthome.online/capturas/tel1.jpg" alt="screenshot" />
  </div>
  <div align="center"> 
    <img src="https://parasmarthome.online/capturas/tel2.jpg" alt="screenshot" />
  </div>
  <div align="center"> 
    <img src="https://parasmarthome.online/capturas/tel3.jpg" alt="screenshot" />
  </div>
</div>

<br />

<!-- Funciones -->
### :gear: Funciones
  
  <h2>Sección principal</h2>
  
  <p>
      Permite la captura de texto para encriptarlo bajo unas llaves (caracteres sustitutos), para convertir el texto agregando dichas llaves haciendolo más complejo de interpretar. LA app tiene las características de responsividad, es decir, que puede ser usada en diferentes dispositivos con tamaños de pantalla diferentes y el contenido se adaptará al tamaño y tipo de dispositivo mostrando u ocultando algunos objetos según el tamaño de pantalla.
  </p>
    

    Cuenta con:

       
 - Botón para encriptar
 - Botón para desncriptar
 - Botón de copar
 - Sección para encío de mensaje encriptado
 - Cajade texto (textarea), para capturar el mensaje a encriptar
 - Título e indicaciones para el usuario
 - Sección de imagen y textos (article), para agrupar imagen inicial y textos
 - Sección footer con leyenda e iconos de redes sociales y organizaciones de programa de formación
 
 
 <h2>Sección envíar mensaje encriptado</h2>
 
 <p>
      La sección para envío de mensaje, se encuentra oculta hasta que el usuario pulsa el botón "Copiar", mostrando la sección de enviar mensaje por WhatsApp y mostrando otros objetos para que el usuario captur los datos necesarios para el envío.
</p>


<p>Los objetos que se encuentran en la sección son:</p>
      
    - Mensaje encriptado
    - Caja de texto para número telefónico destino
    - Botón para "Enviar mensaje"
    - Botón de "Regresar"
    - Botón de "Recargar página"

<p>Datos a capturar:</p>
       
 - Número telefónico válido para WhatsApp (clave de país) + (área) + (número local)
 
<br />

<!-- Validaciones -->
### :heavy_check_mark: Validaciones

- Captura de texto únicamente en minúzculas
- Acepta números
- No permite caracteres con acentos
- No permite encriptar / desencriptar si el campode captura se ncuentra vacio
- Valida al enviar mensaje encriptado que el número tenga los mínimos datos (dato numérico, clave país, numero de área y npumero local)

 <br />


<!-- Flujo de usuario -->
### :arrows_counterclockwise: Flujo de usuario

<p>1. El usuario escribe un mensaje para encriptar</p>
<p>2. Hacer clieck en el botón "Encriptar"</p>
<p>3. La imagen de la derecha y los textos con mensaje al usuario se ocultarán para poder mostrar el texto encriptado</p>
<p>4. El usuario podrá visualizar el botón "Copiar" para que se guarde en el portapapeles</p>
<p>5. El mensaje podrá ser desencriptado al pegarlo en la caja de texto principal y haciendo click en el botón "Desencriptar"</p>
<p>6. Al hacer click en el botón "Copiar", se vizualizará una nueva sección con el botón "Enviar mensaje"</p>
<p>7. Al hacer click sobre el botón "Enviar mensjae", se mostrará la sección de enviar mensaje por WhatsApp</p>
<p>8. Para enviar el mensaje encriptado pora la aplicaci´n de mensajería WhatsApp se requiere la captura de un número telefónico válido para WhatsApp</p>
<p>9. Una vez capturado el número será validado al hacer click en el botón "Enviar mensaje"</p>
<p>10. El usuario puede regresar a la sección de encriptar mensaje o recargar página haciendo click en los botones del mismo nombre.</p>

Nota, Al hacer click en los botones "Regresar" y "Recargar página", la sección de envir mensaje por WhatsApp se ocultará nuevamente.

 <br />


<!-- Mensaje WhatsApp -->
### :arrows_counterclockwise: Mensaje WhatsApp

<p>Una vez que el mensjae sea encriptado y el número destino validado al hacer click en el botón "Enviar mensjae", la app web solicitará abrir la API de watsapp para formato web (navegador web), y la app de dispositivo segpun el SO que se use.
El el caso de una PC se deberá tener en cuenta que puede requerir dar permisos para abrir una nueva ventana a la aplicación web de mensajería seleccionar las opciones necesarias y una vez abierto "web.whatsapp", enviar el mensaje.
La aplicación de WhatsApp validará que el número destino sea válido y que exista vinculado a un cliente, de lo contrario no podrá ser enviado el mensjae.
El contenido del mensaje mostrará</p>
<div align="center"> 
    <h2>Mensaje de a enviar</h2>
    <img src="https://parasmarthome.online/capturas/mensjajewa.jpg" alt="screenshot" />
  </div>
 <br />
 
 
 
 https://github.com/deepsodome/codificar-mensaje.git
 
 git remoto agregar origen https://github.com/deepsodome/codificar-mensaje.git
 git rama -M principal 
git push -u origen principal
