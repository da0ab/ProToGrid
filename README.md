

# ProToGrid

A simple and easily expandable CSS grid system
***
**Base grid class**
- grid-2
- grid-3
- grid-4
- grid-5
- grid-6
- grid-1-2
- grid-2-1
- grid-1-3
- grid-3-1

**Easy class creation thanks to css**
```HTML
[class*=grid-] {
   clear: both;
   display: grid;
   gap: var(--gap, 1vw);
   margin-bottom: var(--g-m-b, 1vw);
   grid-template-columns: var(--col);
}
```
**Inline style**
class="grid-" style="--col: 1fr 7fr"

class="grid-3" style="--gap: 18rem"

class="grid-4" style="--phone-col: 1fr 1fr 1fr





***

# Docs https://da0ab.github.io/ProToGrid/


