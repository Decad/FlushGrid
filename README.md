**FlushGrid**

FLushGrid solves a different problem to a normal css grid, flush grid has no gutters and using `box-sizing: border-box;` adding padding on any grid will not change the size of the colomn and thus break the grid.

Due to no gutters FlushGrid has no wrapping elements around each section or any additional classes to add to the first or last coloumns in a row.

Flushgrid was developed as I needed a css grid for creating an application that was designed to have many sections sitting flush together and it was becoming a pain to work with a grid system that had gutters.


***Example***
``` html
    <div class="col6"></div>
    <div class="col3"></div>
    <div class="col3"></div>
```

For more examples see the example page.