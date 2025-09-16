## Nano cambia de disfraz

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

Haz que Nano se emocione cambiando **disfraces**.

Los objetos tienen **disfraces** para cambiar su apariencia. They are usually slightly different images of the same sprite. Para animar un objeto, puedes cambiar su disfraz.

</div>
<div>

![El objeto Nano diciendo, "¡Gracias!"](images/nano-step2.png){:width="300px"}

</div>
</div>

--- task ---

Agrega el objeto **Nano** a tu proyecto desde la categoría **fantasía**.

![El ícono "elegir un objeto".](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Asegúrate de que el objeto **Nano** esté seleccionado en la lista de objetos debajo del escenario.

![La lista de objetos, con un borde azul alrededor del objeto Nano para mostrar que está seleccionado.](images/nano-selected.png)

Haga clic en la pestaña **Código** y agrega el código para hacer que el objeto **Nano** diga 'Gracias' usando `cambiar disfraz`{:class="block3looks"} y `esperar`{:class="block3control"}: Use the drop down menu to switch between `nano-b`{:class="block3looks"} and `nano-a`{:class="block3looks"}:

![El objeto Nano.](images/nano-sprite.png)

```blocks3
when this sprite clicked // cuando se hace clic en Nano
switch costume to [nano-b v] // Nano hablando
wait (0.5) seconds // intenta 0.25 en lugar de 0.5
switch costume to [nano-a v] // Nano sonriendo
```
--- /task ---

**Consejo:** Todos los bloques están codificados por colores, por lo que encontrarás el `cambiar disfraz a `{:class="block3looks"} en el menú de bloques `apariencia`{:class="block3looks"} y el bloque de `espera`{:class="block3control"} en el menú de bloques `Control`{:class="block3control"}.

--- task ---

**Prueba:** Haz clic en el objeto **Nano** en el escenario y verifica que cambie su disfraz.

--- /task ---
