Introduction to 2D layouts in CSS Grid
====

Krakow, 30.05.2018

https://github.com/cyprianos/css-grid-presentation

### Motivation
* finally, some real solution to 2d layouts 
* tricks vs support
* CSS Grid is well supported in new browsers
* CSS will becomes production standard in couple years

### Questions:
* How many folks does use flexbox?
* who still uses float:left or inline block?
* who uses CSS Grid on production?

### What we have used?
* table
* float:left 
* display: inline-block
* column-count: 3;
* calc(100% - 80px);
* preprocessor
* bootstrap :/ ugh
* Mutation Observers
* flexbox

### Basic demo
* https://codepen.io/cyprianos/pen/xzxQXg?editors=1100
* display:grid
* grid-template-columns:200px 400px 
* grid-gap

### Functions
* repeat(3, 1fr) 200px
* grid-template-columns: minmax(100px, max-content)

### Flexibility
* 1fr

### Naming things
* https://codepen.io/anon/pen/PaoMYL?editors=1100
* lines: grid-template-columns 200px [a-start] 400px [a-end]
* areas
* areas: dot syntax for empty grid item

### ordering and spanning elements
* z-index
* order
* grid-column, grid-row

### Responsive example
* @media (min-width:600px)

### auto features
* sparse

### Support
* google: caniuse 


### Questions?
* MDN
* https://gridbyexample.com/examples/

....

### About Me
Cyprian Gepfert Codete/Avenade developer, boxing, chess, board games and guitar fan and frontend dependencies hater :)
