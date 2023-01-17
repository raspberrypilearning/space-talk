## Nano cambia de disfraz

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Haz que Nano se emocione cambiando **disfraces**.

Los objetos tienen **disfraces** para cambiar su apariencia. Para animar un objeto, puedes cambiar sus disfraces.

</div>
<div>

![El objeto Nano diciendo, "¡Gracias!"](images/nano-step2.png){:width="300px"}

</div>
</div>

### Nano dice "¡Gracias!"

--- task ---

Agrega el objeto **Nano** a tu proyecto desde la categoría **Fantasía**.

![El ícono "Elegir un objeto".](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Asegúrate de que el objeto **Nano** esté seleccionado en la lista de objetos debajo del escenario.

![La lista de objetos, con un borde azul alrededor del objeto Nano para mostrar que Nano está seleccionado.](images/nano-selected.png)


Haga clic en la pestaña **Código** y agrega el código para hacer que el objeto **Nano** diga 'Gracias' usando `cambiar disfraz`{:class="block3looks"} y `esperar`{:class="block3control"}:

![El objeto Nano.](images/nano-sprite.png)

```blocks3
when this sprite clicked // cuando se hace clic en Nano
switch costume to [nano-b v] // Nano hablando
wait (0.5) seconds // intenta 0.25 en lugar de 0.5
switch costume to [nano-a v] // Nano sonriendo
```
--- /task ---

**Consejo:** Todos los bloques están codificados por colores, así que encontrarás el bloque `cambiar disfraz a`{:class="block3looks"} en el menú de bloques `Apariencia`{:class="block3looks"} y el bloque de `espera`{:class="block3control"} en el menú de bloques `Control`{:class="block3control"}.

--- task ---

**Prueba:** Haz clic en el objeto **Nano** en el escenario y verifica que Nano cambie su disfraz.

--- /task ---

### Nano usa lenguaje de señas

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">Millones de personas utilizan el lenguaje de señas para comunicarse. Una forma común de firmar 'Gracias' es colocar los dedos en la barbilla con la mano lo más plana posible. Luego mueve la mano hacia adelante, alejándola de la barbilla y ligeramente hacia abajo. 
</p>

<!--- Add a video of someone signing --->

Nano usará el lenguaje de señas cambiando de disfraz.

Puedes editar los disfraces para tus objetos con el editor de dibujo. Editarás un disfraz de Nano para que diga 'gracias'.

--- task ---

Haz clic en la pestaña **Disfraces** para ver los disfraces del objeto **Nano**:

![Disfraces disponibles para el objeto Nano.](images/nano-costumes.png)

--- /task ---

--- task ---

Haz clic en el disfraz **nano-b**. Haz clic en el brazo del lado izquierdo y luego haz clic en **Eliminar**.

![El disfraz de nano-b con el brazo seleccionado.](images/nano-arm-selected.png)

El disfraz debería verse así:

![El disfraz de nano-b con el brazo eliminado.](images/nano-arm-deleted.png)

--- /task ---

**Consejo:** Si cometes un error en el editor de dibujos, puedes hacer clic en **Deshacer**.

![El icono 'Deshacer'.](images/nano-undo.png)

--- task ---

Ve al disfraz **nano-c** y haz clic en el brazo en el lado izquierdo, luego haz clic en **Copiar**.

![El disfraz nano-c con el brazo seleccionado.](images/nano-c-arm-selected.png)

--- /task ---

--- task ---

Vuelve al disfraz **nano-b** y haz clic en **Pegar**. El disfraz debería verse así:

![El disfraz de nano-b con el brazo del disfraz de nano-c.](images/nano-b-new-arm.png)

--- /task ---

--- task ---

**Prueba:** Haz clic en el objeto **Nano** en el Escenario y verifica que aparezca la burbuja de diálogo y que el disfraz de Nano cambie al disfraz que has editado.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">Has aprendido a decir "gracias" con signos. La próxima vez que agradezcas a alguien, ¿por qué no utilizas tu nueva habilidad?
</p>

