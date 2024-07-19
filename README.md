<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Markdown with CSS</title>
    <link rel="stylesheet" href="css/styles.css">
</head>

# ProToGrid
css ProTo Grid Micro Sistem

A simple and easily expandable CSS grid system
# Docs https://da0ab.github.io/ProToGrid/


           ProToGrid Micro Sistem

 ┏┓    ┏┳┓  ┏┓  • ┓  ┳┳┓•       ┏┓•
 ┃┃┏┓┏┓ ┃ ┏┓┃┓┏┓┓┏┫  ┃┃┃┓┏┏┓┏┓  ┗┓┓┏╋┏┓┏┳┓
 ┣┛┛ ┗┛ ┻ ┗┛┗┛┛ ┗┗┻  ┛•┗┗┗┛ ┗┛  ┗┛┗┛┗┗ ┛┗┗
            

### GRID

#### Base

**div class="grid-2"** **OR** **ul class="grid-2"**

*   1 of 2
*   2 of 2

**div class="grid-3"** **OR** **ul class="grid-3"**

1 of 3

2 of 3

3 of 3

**div class="grid-4"** **OR** **ul class="grid-4"**

1 of 4

2 of 4

3 of 4

4 of 4

**class="div grid-5"** **OR** **ul class="grid-5"**

1 of 5

2 of 5

3 of 5

4 of 5

5 of 5

**class="div grid-6"** **OR** **ul class="grid-6"**

1 of 6

2 of 6

3 of 6

4 of 6

5 of 6

6 of 6

**div class="grid-1-2"** **OR** **ul class="grid-1-2"**

1 of 2

2 of 2

**div class="grid-2-1"** **OR** **ul class="grid-2-1"**

1 of 2

2 of 2

**div class="grid-1-3"** **OR** **ul class="grid-1-3"**

1 of 2

2 of 2

**div class="grid-3-1"** **OR** **ul class="grid-3-1"**

1 of 2

2 of 2

#### Grid inline style

**div class="grid-" style="--col: 1fr 7fr"** **OR** **ul class="grid-" style="--col: 1fr 7fr"**

*   1 of 2
*   2 of 2

#### Gap

**div class="grid-3 gap-0"** **OR** **ul class="grid-3 gap-0"**

*   1 of 3 gap-0
*   2 of 3 gap-0
*   3 of 3 gap-0

**div class="grid-3 gap-2"** **OR** **ul class="grid-3 gap-2"**

*   1 of 3 gap-2
*   2 of 3 gap-2
*   3 of 3 gap-2

**div class="grid-3 gap-3"** **OR** **ul class="grid-3 gap-3"**

*   1 of 3 gap-3
*   1 of 3 gap-3
*   1 of 3 gap-3

**div class="grid-3 gap-4"** **OR** **ul class="grid-3 gap-4"**

*   1 of 3 gap-4
*   2 of 3 gap-4
*   3 of 3 gap-4

#### Gap inline style

**div class="grid-3" style="--gap: 18rem"** **OR** **ul class="grid-3" style="--gap: 18rem"**

*   1 of 3
*   2 of 3
*   3 of 3

### MOBILE GRID

#### Phone

**div class="grid-4 phone-grid2"** **OR** **ul class="grid-4 phone-grid2"**

1 of 4 **OR** 1 of 2 phone

2 of 4 **OR** 2 of 2 phone

3 of 4 **OR** 1 of 2 phone

4 of 4 **OR** 2 of 2 phone

#### Grid phone inline style

**div class="grid-4" style="--phone-col: 1fr 1fr 1fr"** **OR** **ul class="grid-4 phone-grid2"**

1 of 4 **OR** 1 of 3 phone

2 of 4 **OR** 2 of 3 phone

3 of 4 **OR** 3 of 3 phone

4 of 4 **OR** 1 of 3 phone

#### Ipad

**div class="grid-4 ipad-grid2"** **OR** **ul class="grid-4 ipad-grid2"**

1 of 4 **OR** 1 of 2 ipad

2 of 4 **OR** 2 of 2 ipad

3 of 4 **OR** 1 of 2 ipad

4 of 4 **OR** 2 of 2 ipad

**div class="grid-5 phone-grid3"** **OR** **ul class="grid-5 phone-grid3"**

1 of 5 **OR** 1 of 3 ipad

2 of 5 **OR** 2 of 3 ipad

3 of 5 **OR** 3 of 3 ipad

4 of 5 **OR** 1 of 3 ipad

5 of 5 **OR** 2 of 3 ipad

**div class="grid-5 ipad-grid4 ipad-port-grid2"** **OR** **ul class="grid-5 ipad-grid4 ipad-port-grid2"**

1 of 5 **OR** 1 of 4 ipad

2 of 5 **OR** 2 of 4 ipad

3 of 5 **OR** 3 of 4 ipad

4 of 5 **OR** 4 of 4 ipad

5 of 5 **OR** 1 of 4 ipad

#### Grid ipad inline style

**div class="grid-5 ipad-grid ipad-port-grid" style="--ipad-col: 1fr 3fr; --ipad-port-col: 1fr 1fr 2fr"** **OR** **ul class="grid-5 ipad-grid ipad-port-grid" style="--ipad-col: 1fr 3fr; --ipad-port-col: 1fr 1fr 2fr"**

1 of 5 **OR** 1 of 4 ipad

2 of 5 **OR** 2 of 4 ipad

3 of 5 **OR** 3 of 4 ipad

4 of 5 **OR** 4 of 4 ipad

5 of 5 **OR** 1 of 4 ipad

#### Automatic scrolling on your phone

**div class="grid-6 phone-scroll"** **OR** **ul class="grid-6 phone-scroll"**

1 of 6

2 of 6

3 of 6

4 of 6

5 of 6

6 of 6
