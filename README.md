# sparta-global-website
sparta-global-website

This is my website constructed over the past weekend. The following features include Nav bar, Table, , Video, Footer, Links, Profile etc.


  For the Jumbotron i made use of Bootstrap. with the following code below. Included is the links and sources.
``` html
          <head>
                <title>Bootstrap Example</title>
                <meta charset="utf-8">
                <meta name="viewport" content="width=device-width, initial-scale=1">
                <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
                <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
                <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>


                  <title>Jumbotron Template for Bootstrap</title>
                    <link href="./css/bootstrap.min.css" rel="stylesheet">
                    <!-- Custom styles for this template -->
                    <link rel="stylesheet" href="./css/row.css" type="text/css">
          </head>


```

For the nav bar i created a nav bar and included the following tabs
```html
      <nav class="navbar navbar-inverse">
        <div class="container-fluid">
          <div class="navbar-header">
            <a class="navbar-brand" href="#">Home</a>
          </div>
          <ul class="nav navbar-nav">
            <li><a href="Video.html">Video</a></li>
            <li><a href="tables.html">Tables</a></li>
            <li><a href="contact.html">Contact page</a></li>
          </ul>
        </div>
      </nav>
```


For the main body of this index.html i created a class called row and included a left side for the creation of the profile section and the right side for a heading and pseudo text.
```html
      <h2> Unequal Columns</h2>

        <div class="row">
          <div class="column left" style="background-color:#aaa;">
            <h3>Profile</h3>
              <ul> Name  </ul>
              <ul> Job title  </ul>
              <ul> Description  </ul>
              <ul> ..........  </ul>
          </div>
          <div class="column right"> <style="background-color:#bbb;">
            <h2>Heading</h2>
            <p>SLorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies nisi vel augue. Curabitur ullamcorper ultricies nisi.


            SLorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi.</p>
          </div>
        </div>


```

The code for the footer is similar to that of the navbar but the div class has been changed from navbar-header to that of navbar-footer

```html
        <footer>
          <div class="footer">
            <nav class="navbar navbar-inverse">
              <div class="container-fluid">
                <div class="navbar-footer">
                  <a class="navbar-brand" href="#">Home</a>
                </div>
                <ul class="nav navbar-nav">
                  <li><a href="Video.html">Video</a></li>
                  <li><a href="tables.html">Tables</a></li>
                  <li><a href="contact.html">Contact page</a></li>
                </ul>
              </div>
            </nav>
          </div>
        </footer>
```

For the body of html i set the background image to be sourced from internet.
```css
      body {
        margin: 100px;
        background-image: url("http://mdes.rosspatel.com/wp-content/uploads/2015/11/network-connection-35737.jpg");
        text-emphasis-color: white;
        font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
        font-size: 14px;
        line-height: 1.42857143;
        color: #fff;
      }
```

For this page the major feature was the inclusion of a video and a images both sourced locally.
```html
        <div>
        <video width="400" controls>
          <source src="video/videoplayback.mp4" type="video/mp4">
        </video>
```
This is the code used to source the locally stored image file
```html
<div>
<img src="images/social-media-stats-2017.jpg" alt="SocialMediaInfo"
width="800" height="800">
<caption> Sourced from ...</caption>
</div>
```
