-ALL FONT-SIZE ARE IN REM (base 10). 1.4rem = 14px; 3.2rem = 32px

-To change the image of jumbotron, add a class in the div jumbotron, and add a line in style_page.css to change the bg-image

  <div class="jumbotron class_added"></div>

  .class_added {
    background-image: url('../images/image_to_show');
  }

-Immediately after jumbotron, put all your content in a section with the class "container"

  <section class="container">

-For title with the green line, simply put this code in your html:

  <div class="mainTitleContainer">
    <div class="mainTitle">
      <h2>La société</h2>
      <div class="line"></div>
    </div>
  </div>

