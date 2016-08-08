#Jar Responsive Grid
<p>
Jar is a super simple resposnive grid that handles the brakepoints of your layout while you focus on developing.

</p>

#Get Jar

<p>

  *Get up and running by downloading Jar http://kaprilam.github.io/Jar//<br>
  *Get up and running by cloning the repo,(for stable releases download from site or clone from stable branch since the project is in constant development).
</p>

#Jar Quick-Start


<p>
  Jar is very semantic, to make use of the rows and grid you just have to add the class .*row* to a container (either *article* or *div* for better results) and then nest your columns using the size you'd like it to be. </p><br>
 ````Html
    <article class="row">
      <div class="six">
        You'll get a container 6 cols wide based on a 12 cols grid.
      </div>
      <div class="six">
        You'll get a container 6 cols wide based on a 12 cols grid.
      </div>
    </article>
  ````
<h3>What Jar includes out of the box</h3>

1.Offset columns : You can offset columns adding the prefix _.offset-Number of columns_.
<br>
  ````Html
      <article class="row">
        <div class="offset-six">
          Will offset the width equivalent to six
        </div>
      </article>
  ````

2. Choose left or right position for your element, you can either push things to right or left using _.lefty_ or _.righty_ classes.

  ````Html
    <article class="row">
      <nav>
      <span class="lefty">
        Brand(on the left side of nav)
      </span>
        <div class="container>
          nav. links
        </div>
      </nav>
    </article>
  ````

    3.Wrap your content on a full with container or a centralize padded container using _.container-full_ and .container_ classes respectively.
    ````Html
    <div class="container">
      <article class="row">
        <div class="six">
          content
        </div>
        <div class="six">
          more content
        </div>
      </article>
    </div>
    ````
    ````Html
      <div class="container-full">
      <article class="row">
        <div class="six">
          content
        </div>
        <div class="six">
          more content
        </div>
      </article>
    </div>
    ````
  <h3>For more information on how to use Jar</h3>
    [Checkout Jar Grid here](http://kaprilam.github.io/jar//)
    
