

# ProToGrid

A simple and easily expandable CSS grid system by **div** and **ul**
***
### Base grid class

**Equal class:**

 grid-2, grid-3, grid-4,  grid-5, grid-6 
 
**Not equalclass:**

grid-1-2, grid-2-1, grid-1-3, grid-3-1



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

### Grig gap base class

gap-0, gap-2, gap-3, gap-4

**Gap inline style**
```HTML
class="grid-3" style="--gap: 18rem;"
```


## Mobile

**Default phone grid** screen size max-width: 769px

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


**Pad grid** screen size min-width: 769px and max-width: 1024px

Simply saves the mesh
```HTML
class="grid-3 .pad-grid" 
```

Changes the number of cells to 2
```HTML
class="grid-3 .pad-grid2" 
```

Changes the number of cells to 3
```HTML
class="grid-4 .pad-grid2" 
```
**Pad inline style**

```HTML
class="grid-4" style="--pad-col: 1fr 1fr 1fr;"
```

**Pad orientation portrait grid** 

Simply saves the mesh
```HTML
class="grid-3 pad-port-grid" 
```
Changes the number of cells to 2
```HTML
class="grid-3 .pad-port-grid2" 
```

**Pad portrait inline style**

```HTML
class="grid-4" style="--pad-port-col: 1fr 1fr 1fr;"
```

## Bonus

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

### Swap places on the phone

```HTML
    <div class="grid-2 phone-revers">
        <div>
           1 of 2
        </div>
        <div>
           2 of 1
       </div>
    </div>
```

## Helper classes


```HTML
class="phone-show"
```
```HTML
class="phone-hide"
```
```HTML
class="pad-hide"
```
```HTML
class="pad-show"
```


***

## Demo

https://da0ab.github.io/ProToGrid/


