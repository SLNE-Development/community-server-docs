# Sonstiges

<tabs>
<tab title="Befehle" id="plot-commands">

<deflist>
<def title="Besitzer herausfinden" id="plot-get-owner">

Um den Besitzer eines Grundstücks herauszufinden, nutze den Befehl `/pwho` während du auf einem Grundstück stehst.

</def>
</deflist>

<deflist>
<def title="Feststecken" id="plot-unstuck">

Solltest du auf einem fremden Grundstück feststecken, kannst du `/unstuck` verwenden, um wieder
zum Spawn zu gelangen.
> Der Missbrauch dieses Befehls wird als Exploiting gewertet und bestraft!
>
{style="warning"}

</def>
</deflist>
</tab>

<tab title="Weiteres" id="plot-other">
<deflist>
<def title="Grundstücksnachrichten" id="plot-messages">  

Beim Betreten oder Verlassen eines Grundstückes bekommst du im Chat eine Nachricht.
Diese Funktion lässt sich jedoch ein- oder ausschalten.

1. Führe hierzu den Befehl `/protect` im Chat aus.
2. Klicke anschließend auf die Lederschuhe. ![toggle plotmessage](plot-toggle-plotmessage.png)

</def>
</deflist>
</tab>

<tab title="Berechnung" id="plot-calculation">

<deflist>
<def title="Berechnung des Grundstückes" id="plot-price-calculation">

$$
p(d) = \max( 4, - \frac {d} {600} + \frac {37} {3} )
$$

Hierbei gilt:

- `p(d)` ist der berechnete Preis pro Block.
- `d` ist die Distanz vom Grundstück zum Spawn, gemessen in Blöcken.

</def>
</deflist>

</tab>
</tabs>
