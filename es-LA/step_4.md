## Pico reproduce un sonido

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Otra forma de comunicarse es utilizar el sonido.
</div>
<div>

![El objeto Pico diciendo, "¡Hola!"](images/pico-step2.png){:width="300px"}

</div>
</div>

### Añade un sonido al objeto Pico

--- task ---

Haz clic en la pestaña **Sonidos** para el objeto **Pico** y encontrarás el sonido **pop**. Haz clic en el triangulo **Reproducir** para escuchar el sonido **pop**.

![Reproduciendo el sonido pop en la pestaña Sonidos.](images/pico-sound-play.png)

**Debug**: Si no puedes escuchar un sonido, verifica que el sonido funciona en tu computadora o tableta.

--- /task ---

--- task ---

Para elegir un nuevo sonido, haz clic en el ícono **Elige un sonido** y selecciona la categoría **Espacio** o escribe `space` en el cuadro de búsqueda.

![El icono 'Elige un sonido'.](images/sound-button.png)

![El editor de Scratch con 'Elige un sonido' resaltado.](images/pico-choose-sound.png)

![La categoría 'Espacio' en la Biblioteca de sonidos.](images/pico-space-category.png)

--- /task ---

--- task ---

Reproduce algunos sonidos diferentes usando los íconos **Reproducir**. Una vez que hayas encontrado el sonido que deseas utilizar, haz clic en él para agregarlo a tu proyecto.

![Un ejemplo de sonido (el sonido Alien Creak1) que se muestra debajo del sonido pop en la pestaña Sonidos.](images/pico-inserted-sound.png)

--- /task ---

### Haz que el sonido se reproduzca al hacer clic (o tocar)

--- task ---

Haz clic en la pestaña **Código**. En el menú de bloques `Sonido`{:class="block3sound"}, busca el bloque `iniciar sonido`{:class="block3sound"}.

Arrastra el bloque al área de Código, entre el bloque `al hacer clic en este objeto`{:class="block3events"} y el bloque `decir`{:class="block3looks"}. Se abrirá un espacio y el bloque encajará en su lugar.

![El bloque de 'iniciar sonido' se agrega entre los dos bloques.](images/pico-insert-block.gif)

Tu código debe parecerse a esto:

![El objeto Pico.](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Hello!] for [2] seconds // hide speech after 2 seconds
```

--- /task ---

### Prueba tu código

--- task ---

Comprueba que tu bloque `iniciar sonido`{:class="block3sound"} tiene el sonido que elegiste. Si no es así, debes hacer clic en el sonido en el bloque `iniciar sonido`{:class="block3sound"}, y después selecciona el sonido elegido en el menú desplegable.

![Haciendo clic en el sonido Alien Creak1 en el menú desplegable dentro del bloque 'iniciar sonido'.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Prueba:** Haz clic en el objeto **Pico** y verifica que la burbuja de dialogo aparece y que puedes escuchar el sonido. Si no escuchas el sonido, asegúrate de haber agregado el bloque `iniciar sonido`{:class="block3sound"} debajo del bloque `al hacer clic en este objeto`{:class="block3events"}.

--- /task ---

