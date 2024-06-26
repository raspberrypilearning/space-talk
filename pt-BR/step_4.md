## Pico toca um som

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Outra forma de se comunicar é usar som.
</div>
<div>

![O ator Pico falando, "Olá!"](images/pico-step2.png){:width="300px"}

</div>
</div>

### Adicionar um som ao ator Pico

--- task ---

Clique na aba **Sons** para o ator **Pico** e você encontrará um som chamado **pop**. Clique no **Jogar** para ouvir o som **pop**.

![Reproduzindo o som pop na aba Sons.](images/pico-sound-play.png)

**Depurar**: Se você não consegue ouvir um som, verifique se o som está funcionando em seu computador ou tablet.

--- /task ---

--- task ---

Para escolher um novo som, clique no ícone **Selecionar um Som** e selecione a categoria **Espaço** ou digite `space` na caixa de pesquisa.

![O ícone 'Selecione um som'.](images/sound-button.png)

![O editor Scratch com 'Selecionar um Som' destacado.](images/pico-choose-sound.png)

![A categoria 'Espaço' na Biblioteca de sons.](images/pico-space-category.png)

--- /task ---

--- task ---

Reproduza alguns sons diferentes usando os ícones **Reproduzir**. Depois de encontrar o som que deseja usar, clique nele para adicioná-lo ao seu projeto.

![Um exemplo de som (o som Alien Creak1) mostrado abaixo do som pop na guia Sons.](images/pico-inserted-sound.png)

--- /task ---

### Faça o som tocar quando clicado (ou tocado)

--- task ---

Clique na guia **Código**. No menu de blocos `Som`{:class="block3sound"}, encontre o bloco `toque o som`{:class="block3sound"}.

Arraste o bloco para a área de código, entre `quando este ator for clicado`{:class="block3events"} e o bloco `diga`{:class="block3looks"}. Um espaço se abrirá e o bloco se encaixará no lugar.

![O bloco de 'toque o som' sendo adicionado entre os dois blocos.](images/pico-insert-block.gif)

Seu código deve ficar assim:

![O ator Pico.](images/pico-sprite.png)

```blocks3
when this sprite clicked
+start sound [Alien Creak1 v] 
say [Olá!] for [2] seconds // esconder a fala após 2 segundos
```

--- /task ---

### Teste seu código

--- task ---

Verifique se o seu bloco `toque o som`{:class="block3sound"} contém o som escolhido. Caso contrário, você precisa clicar no som no bloco `toque o som`{:class="block3sound"} e, em seguida, selecionar o som escolhido no menu suspenso.

![Clicando no som Alien Creak1 no menu suspenso dentro do bloco 'toque um som'.](images/pico-sound-menu.png)

--- /task ---

--- task ---

**Teste:** Clique no ator **Pico** e verifique se o balão de fala aparece e você pode ouvir o som. Se você não ouvir o som, certifique-se de ter adicionado o bloco `toque o som`{:class="block3sound"} abaixo do bloco `quando este ator for clicado`{:class="block3events"}.

--- /task ---

