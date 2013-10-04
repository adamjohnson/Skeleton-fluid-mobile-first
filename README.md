# Fluid Mobile First Skeleton Grid

A fluid, mobile first version of Dave Gamache's Skeleton. Starting at mobile sizes and moving fluidly up to a max-width of 1200px.

## How to implement the Grid System

Nothing has changed here from Dave Gamache's original implementation. Just wrap your page with a `.container` class, then add things like `five` `columns`, et all, to your markup. Eg:

    <div class="container">
  
      <!-- Give column value in word form (one, two..., sixteen) -->
      <div class="sixteen columns">
        <h1>Full Width Column</h1>
      </div> <!-- /.sixteen.columns -->
      
      <!-- You can push over by columns -->
      <div class="five columns offset-by-one"></div>

    </div> <!-- /.container -->

See the provided `index.html` file for a more complete example and to play around.

### Credits
 
 * More information about Skeleton: http://getskeleton.com
 * Originally created by Dave Gamache: http://davegamache.com
 * Made mobile first by Adam Johnson: http://adamjohnsondesign.com
 * Original fluid credit goes to William Skates: https://github.com/WillSkates/Skeleton/blob/master/stylesheets/skeleton-fluid.css
