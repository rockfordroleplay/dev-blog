# log-sistemas
**Rockford Juego de Rol, 2020 ― próximamente.**

Dentro de este documento serán mencionados y específicados todos los sistemas que yacen en el servidor. Para visualizar las imágenes y/o por alguna consulta rediríjase a nuestro [discord oficial](https://discord.gg/sQfqWfX).

## [Repositorio]

## [1.0.1] - Sistema celular
*Utilizable de 2 diferentes maneras*

La primera es a través de una interfaz interactiva en TextDraws. El segundo por parte de los comandos /sms, /llamar, etc.

- **/telefono** para abrir el panel interactivo de teléfono. El personaje tendrá un objeto en su mano y el TextDraw se mostrará en la pantalla del jugador. Para desbloquear el teléfono, simplemente se da click en el texto “Toca para desbloquear” que se encuentra debajo de la pantalla. Las notificaciones se mostraran tanto en el chat local como en la pantalla del celular. Incluye la opción de ver el historial de mensajes y llamadas, y se resaltan en sus colores. Entonces, por ejemplo, una llamada perdida se resaltará con el color rojo en la pantalla indicando la fecha y hora exacta de la llamada y lo contrario en verde. Al recibir una llamada, los jugadores que estén cerca podrán escuchar la melodía de llamada, y su texto aparecerá frente a usted.

## [1.0.2] - Sistema de silenciadores para armas de bajo calibre y miras ópticas para rifles
Cuando se pone un silenciador en 9mm, se reproduce la animación y el arma se convierte en un 9mm silenciado.
Si pones una mira óptica en el Rifle, se convierte en un Rifle de Francotirador.
Las miras ópticas se venden en las tiendas de armas y en el mercado negro. El silenciador se vende solo en el mercado negro.

- **/optica** - para quitar/poner la mira óptica en el Rifle.
- **/silenciador** - para quitar/poner el silenciador en la 9mm.

## [1.0.3] - Sistema de guardado de armas/objetos en vehículos
Otorga la posibilidad de editar la posición del arma dentro del maletero o en la cabina, además de otros objetos visuales para el vehículo, al retirar un arma retomará la posición configurada del arma en el cuerpo del personaje.

- **/maletero - /observar - /ajustar - /tomararma**
