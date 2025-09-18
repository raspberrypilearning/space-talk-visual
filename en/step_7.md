## Giga changes colour

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

</div>
<div>

![The Giga sprite thinking, "Hmm...".](images/giga-step2.png){:width="300px"}

</div>
</div>

--- no-print ---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; border-radius: 20px; box-shadow: 0 0 15px #3fb654; overflow: hidden;">
<iframe
    src="https://www.youtube.com/embed/_LvVMQjOfmY?rel=0&cc_load_policy=1"
    style="position: absolute; inset: 0; width: 100%; height: 100%; border: none;"
    allowfullscreen>
</iframe>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">

Follow along the project on our [YouTube](7) playlist!
</p>
--- /no-print ---

### Make Giga change colour

--- task ---

Add the **Giga** sprite. 

Drag the **Giga** sprite to the right-hand side of the Stage.

--- /task ---

--- task ---

Add blocks to make **Giga** change colour. 

```blocks3
when this sprite clicked
set [color v] effect to [0] // 0 is the starting colour
think [Hmm...] for [2] seconds 
clear graphic effects // back to the starting colour
```

--- /task ---

--- task ---

Try different numbers from `1` to `200` in the `set color effect to`{:class="block3looks"} block to find a colour you like. 

--- /task ---

--- task ---

Change the words and number of seconds in the `think`{:class="block3looks"} block.

--- /task ---

--- task ---

**Test:** Click **Giga** and check the sprite changes colour and shows a thought bubble.

--- /task ---