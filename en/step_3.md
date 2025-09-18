## Pico says hello

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
  
Make Pico emote with words and sound.
</div>
<div>

![The Pico sprite saying, "Hello!"](images/pico-step2.png){:width="300px"}

</div>
</div>

--- no-print ---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; border-radius: 20px; box-shadow: 0 0 15px #3fb654; overflow: hidden;">
<iframe
    src="https://www.youtube.com/embed/wZU1QGnKG8c?rel=0&cc_load_policy=1"
    style="position: absolute; inset: 0; width: 100%; height: 100%; border: none;"
    allowfullscreen>
</iframe>
</div>

--- /no-print ---

### Make Pico talk

--- task ---

Open the the `Events`{:class="block3events"} blocks menu and drag a `when this sprite clicked`{:class="block3events"} block to the Code area.

```blocks3
+when this sprite clicked
```

--- /task ---

--- task ---

Open the `Looks`{:class="block3looks"} menu and drag the `say`{:class="block3looks"} `Hello!` `for`{:class="block3looks"} `2` `seconds`{:class="block3looks"} under your `when this sprite clicked`{:class="block3events"} block.

The blocks will snap together.

```blocks version=hc-3
+when this sprite clicked
say [Hello!] for [2] seconds // hide speech after 2 seconds
```
{: .blocks-hc}

--- /task ---

### Test

--- task ---

**Test:** Click **Pico** and check that the speech bubble appears for two seconds.

--- /task ---

You have already saved your project and given it a name. Scratch will now **automatically** save for you. 

You can still click save if you like, just to make sure.
