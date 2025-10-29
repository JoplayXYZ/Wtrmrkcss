# Project Wtrmrkcss
Project WTRMRK: A css file for having a cool looking watermark on your site

```diff
    ▄▄▌ ▐ ▄▌▄▄▄▄▄▄▄▄  • ▌ ▄ ·. ▄▄▄  ▄ •▄     ▄▄· .▄▄ · .▄▄ · 
    ██· █▌▐█•██  ▀▄ █··██ ▐███▪▀▄ █·█▌▄▌▪   ▐█ ▌▪▐█ ▀. ▐█ ▀. 
    ██▪▐█▐▐▌ ▐█.▪▐▀▀▄ ▐█ ▌▐▌▐█·▐▀▀▄ ▐▀▀▄·   ██ ▄▄▄▀▀▀█▄▄▀▀▀█▄
    ▐█▌██▐█▌ ▐█▌·▐█•█▌██ ██▌▐█▌▐█•█▌▐█.█▌   ▐███▌▐█▄▪▐█▐█▄▪▐█
     ▀▀▀▀ ▀▪ ▀▀▀ .▀  ▀▀▀  █▪▀▀▀.▀  ▀·▀  ▀ ▀ ·▀▀▀  ▀▀▀▀  ▀▀▀▀ 
```
## Examples:

[![]()]
## Useage:

### Import the CSS file using jsdelivr CDN

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/JoplayXYZ/Wtrmrkcss@latest/wtrmrk.css">
```

### Required classes

- wtrmrk

The content of the div **has** to be an image

Example Structure:
```html
<div class="wtrmrk">
    <img src="https://minotar.net/helm/JoplaydotXYZ/60.png" alt="Watermark">
</div>

```
Example Structure with modifiers:

- bottom-left

- rounded

- large

- pixel
```html
<div class="wtrmrk bottom-left rounded large pixel">
    <img src="https://minotar.net/helm/JoplaydotXYZ/60.png" alt="Watermark">
</div>

```
### Alignment classes

- bottom-right
- bottom-left
- top-right
- top-left

### Modifier classes

- rounded: 12px corner radius

- small: 30px width

- large: 120px width

- faint: 0.1 opacity

- pixel: pixelated rendering

### Shift classes

**5px:**

- shift-up-5
- shift-down-5
- shift-left-5
- shift-right-5

**10px:**

- shift-up-10
- shift-down-10
- shift-left-10
- shift-right-10
