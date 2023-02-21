<h1 align="center"> 🏆  <strong> Challenge ONE | Conversor De Moneda </strong> </h1>
<h2>⚡ <strong>Descripción</strong></h2>

<p>En esta oportunidad, a los Devs se nos solicitó crear un conversor de divisas utilizando el lenguaje Java. Las características solicitadas por nuestro cliente son las siguientes:</p>

<h2>🚨 <strong>Requisitos:</strong></h2>
<p>- El convertidor de moneda debe:</p>

<ul>
  <li>Convertir de la moneda de tu país a Dólar</li>
  <li>Convertir de la moneda de tu país  a Euros</li>
  <li>Convertir de la moneda de tu país  a Libras Esterlinas</li>
  <li>Convertir de la moneda de tu país  a Yen Japonés</li>
  <li>Convertir de la moneda de tu país  a Won sul-coreano</li>
</ul>

<p>Recordando que también debe ser posible convertir inversamente, es decir:</p>

<ul>
  <li>Convertir de Dólar a la moneda de tu país</li>
  <li>Convertir de Euros a la moneda de tu país</li>
  <li>Convertir de Libras Esterlinas a la moneda de tu país</li>
  <li>Convertir de Yen Japonés a la moneda de tu país</li>
  <li>Convertir de Won sul-coreano a la moneda de tu país</li>
</ul>

<h2><strong>Extras:</strong></h2>
<p>Como desafío extra te animamos a que dejes fluir tu creatividad, si puedo convertir divisas, ¿tal vez pueda añadir a mi programa otros tipos de conversiones como temperatura por ejemplo?</p>

<h2>⚙️ <strong>Funcionamiento:</strong></h2>

<p>Al iniciar la aplicación se da la opción de elegir entre el conversor de divisas o el conversor de velocidad, en este caso se utilizará el conversor de divisas</p>

<h1><img src="https://i.postimg.cc/j2vwG03g/menuprinicpal.png" alt="menuprinicpal" width="500"/></h1>

<p>Nos enviara a una pagina diferente en la cual podremos trabajar con las divisas disponibles desde una API</p>

<h1><img src="https://i.postimg.cc/T1bWttBh/conversorimporte.png" alt="conversorimporte" width="350"/></h1>

<p>En caso de que se ingrese un valor que no sea válido o no se ingrese ningún valor, se mostrará un mensaje de error</p>

<h1><img src='https://i.postimg.cc/43BhYkb6/valorinvalidoimporte.png' alt='valorinvalidoimporte' width="350"/></h1>

<p>Presionando el boton de salir muestra un cuadro para elegir si se quiere utilizar otro conversor o se quiere terminar con el programa</p>

<h1><img src='https://i.postimg.cc/yYC1FpN2/salirimporte.png' alt='salirimporte' width="350"/></h1>

<p>En el caso de que se decida terminar terminar el programa, se mostrará un mensaje al usuario donde se indique "Programa Terminado"</p>

<h1><img src='https://i.postimg.cc/zBP7RPYQ/finalizarprograma.png' alt='finalizarprograma' width="350"/></h1>

<p>En el caso de que haya elegido otro conversor lo llevara nuevamente a la pantalla principal para poder seleccionarlo</p>

<p>Nos enviara a una pagina diferente en la cual podremos trabajar con las velocidades disponibles</p>

<h1><img src='https://i.postimg.cc/zXMnSRMy/conversorvelocidad.png' alt='conversorvelocidad' width="350"/></h1>

<p>En caso de que se ingrese un valor que no sea válido o no se ingrese ningún valor, se mostrará un mensaje de error</p>

<h1><img src='https://i.postimg.cc/NGX4JD61/valorinvalidovelocidad.png' alt='valorinvalidovelocidad' width="350"/></h1>

<p>Presionando el boton de salir muestra un cuadro para elegir si se quiere utilizar otro conversor o se quiere terminar con el programa</p>

<h1><img src='https://i.postimg.cc/zvqFRZy8/finalizarvelocidad.png' alt='finalizarvelocidad' width="350"/></h1>

<p>En el caso de que se decida terminar terminar el programa, se mostrará un mensaje al usuario donde se indique "Programa Finalizado"</p>

<h1><img src='https://i.postimg.cc/zBP7RPYQ/finalizarprograma.png' alt='finalizarprograma' width="350"/></h1>

<h2>⁉️ <strong>¿Qué se utilizó?</strong></h2>
<p>Se Conectó la aplicación con una API de tipos de cambio en tiempo real, ya que las tasas cambian constantemente permitiendo que la aplicación siga funcionando de manera correcta independientemennte del cambio en las tasas monetarias</p>

<p>Se usaron validaciones para que a la hora de ingresar la información se pudiera recibir la respuesta correcta</p>

<p>Se usaron Excepciones como NumberFormatException para poder evitar problemas de parte del programa o del usuario</p>

<p>Se utilizo JFrame para el manejo de interfaces gráficas, permitiendo mostrar una interfaz mucho mas llamativa para el usuario</p>
