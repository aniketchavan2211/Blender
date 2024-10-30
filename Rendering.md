## Rendering 

### Appyling material to multiple objects

select all sprinkles (long and round sprinkles) holding `Shift` key, 
and create Material named Sprinkles, and then press `CTRL + L` then Link Materials. 

<img width="519" alt="{6D543A61-1F9C-4969-B851-ABDA9601BB82}" src="https://github.com/user-attachments/assets/4d0d912f-ec83-4fba-8b0e-9992a4f3cc7b">

### Generating random values per materials

Open Shading Tab,

press `Shift + A`, click `Input` >  `Object Info` Node
then connect `Object Info` Random Node to  `Principled BSDF` Base Color Node,

### Converting values to color
then press `Shift+A` > `Converter` > `Color Ramp`.

### Constant interpolation
Change to constant, add color , by `+`, and select down color adjust to white on scale to lights the color, 

### Appealing sprinkle colors
select the color , you can adjust % of which color you want the most.

this will give a random color to all sprinkles,

### Making metaliic sprinkles Gold and silver

press `CTRL + Shift + D` while selecting color ramp this duplicate with establish connections

you can adjust POSition also, Connect `Color Ramp` Color Node to `Principled BDSF` Metallic Node.

This will convert yellow sprinkle into gold painted sprinkles.

### Adjusting Sprinkles roughness

Again duplicate the `Color Ramp ` using `CTRL + sHIFT + D` this will also copy establish connection,

### Fly Navigation 

<img width="444" alt="{166AAACB-235D-4B82-B826-637F7F612BBD}" src="https://github.com/user-attachments/assets/dfc48caa-9405-4a11-8cf1-427726209e24">
or press `Shift + ~`
this put in setting Camera Mode, `W` from zoom in or `S` for zoom out, left `A`, right `D`, and up `E`, `Q` for down or use arrows of keyboard.
for Numpad ZERO for put in Camera mode.

### Understanding Render engines

Eevee render engine is fast but not accurate in real-world.
use Cycle render engine for real feel, but it slow your computer.

**Final** : 

<img width="684" alt="{A777E787-E0A0-4DEE-A323-991493E24417}" src="https://github.com/user-attachments/assets/bb5e557d-10b8-4a41-a37e-a117e9181e98">
