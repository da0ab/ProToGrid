

# ProToGrid

A simple and easily expandable CSS grid system
***
### Base grid class
- grid-2 
- grid-3
- grid-4
- grid-5
- grid-6
- grid-1-2
- grid-2-1
- grid-1-3
- grid-3-1

**Grig gap base class**

- gap-0
- gap-2
- gap-3
- gap-4

**Gap inline style**
```HTML
class="grid-3" style="--gap: 18rem;"
```
### Easy class creation thanks to css
```HTML
[class*=grid-] {
   clear: both;
   display: grid;
   gap: var(--gap, 1vw);
   margin-bottom: var(--g-m-b, 1vw);
   grid-template-columns: var(--col);
}
```
**New class**

```HTML
.grid-crible-crable-booms {
--gap: 0;
--g-m-b: 1rem;
--col: 1fr 7fr .5fr;
}
```
### Inline style
```HTML
class="grid-" style="--col: 1fr 7fr;"
```
```HTML
class="grid-3" style="--gap: 18rem;"
```
```HTML
class="grid-4" style="--phone-col: 1fr 1fr 1fr;"
```

## Mobile

**Default display block for screen size @media (max-width: 769px)**

```HTML
@media (max-width: 769px) {
    [class*=grid-] {
        display: block;
    }
}
```
```HTML
@media (max-width: 769px) {
[class*=phone-grid], [class*=phone-grid].phone-show {
        display: grid !important;
        --gap: 3vw;
        grid-template-columns: var(--phone-col, --col);
    }
}
```

**Сlasses for saving the grid**

Simply saves the mesh
```HTML
class="grid-3 .phone-grid" 
```

Changes the number of cells to 2
```HTML
class="grid-3 .phone-grid2" 
```

**Phone inline style**

```HTML
class="grid-4" style="--phone-col: 1fr 1fr 1fr;"
```


**Default display block for screen size @media (min-width: 769px) and (max-width: 1024px)**

Simply saves the mesh
```HTML
class="grid-3 .ipad-grid" 
```

Changes the number of cells to 2
```HTML
class="grid-3 .ipad-grid2" 
```

Changes the number of cells to 3
```HTML
class="grid-4 .ipad-grid2" 
```
**Ipad inline style**

```HTML
class="grid-4" style="--ipad-col: 1fr 1fr 1fr;"
```

**Default display block for screen size @media  (min-device-width : 768px) and (max-device-width : 1024px) and (orientation : portrait)** 

Simply saves the mesh
```HTML
class="grid-3 ipad-port-grid" 
```
Changes the number of cells to 2
```HTML
class="grid-3 .ipad-port-grid2" 
```

**Ipad portret inline style**

```HTML
class="grid-4" style="--ipad-port-col: 1fr 1fr 1fr;"
```
### Automatic scrolling on your phone
```HTML
<div class="phone-scroll">
    <div class="grid-6">
        <div>
           1 of 6
        </div>
        <div>
           ... of ...
       </div>
    </div>
</div>
```

***

## Demo

https://da0ab.github.io/ProToGrid/


