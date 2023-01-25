# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
Home.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Lexical</title>
  <style>
  body{
    background-image:url("ss.jpg");
    background-size: cover;
    
   }
   .container{
color: rgb(255, 0, 0);
   }
   .title{
   
      text-align: center;
      font-size: 100px;
      font-family: Georgia, 'Times New Roman', Times, serif;
    }
   * {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: black;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  top: 10px;
  box-shadow: 15px 15px 8px gray;
  background-color: rgb(255, 255, 255);
}

.banner {
  display: block;
  width: 80%;
  height: 10px;
  text-align: center;
  font-size: 60px;
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-weight: bold;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 30px;
  color: rgb(245, 245, 245);

}
.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:green;
  text-align: center;
  padding-top: 20px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}
.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color:aquamarine;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}
.menuitem a {
  text-decoration: none;
  color: #ff000d;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  
  color: white;
  display: inline;
  color: brown;
}
.contenttext{

  color: rgb(25, 0, 255);
}

    </style>
  </head>
  <body>   
    <div class="container">
      <div class="title">LEXICAL</div>
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="product.html">product</a>
           <div class="menuitem"><a href ="People.html">People</a></div>
        <div class="menuitem"><a href="contactus.html">contact us</a></div
        </div>
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="images.jfif" alt="img">
          <div class="contenttext">
            An adventure game is a video game in which the player assumes the role of a protagonist
            in an interactive story driven by exploration and/or puzzle-solving. The genre's focus on 
            story allows it to draw heavily from other narrative-based media, literature and film,
            encompassing a wide variety of literary genres. Many adventure games are designed for
            single player, since this emphasis on story and character makes multiplayer design difficult.
            <br>
            Adventure games continue to be popular in the form of visual novels, which
            make up nearly 70% of PC games released in Japan.Asian countries have also found
            markets for adventure games for portable and mobile gaming devices. Japanese 
            adventure-games tend to be distinct from Western adventure  games and have 
            their own separate development history.
          </div>
        </div>
       
      </div>
      <div class="footer">
        Copyright &#169; 2023  Lexical Private Limited, Developed by praveen S
      </div>
    </div>
  </body>
</html>
```
contactus.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>LEXICAL</title>
    <style>
      * {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-image: url("ss.jpg");
  background-size: cover;
 
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px rgb(0, 51, 255);
  background-color: rgb(129, 173, 255);
}
.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-weight: bold;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: whitesmoke;
}
.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: black;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}
.menuitem a {
  text-decoration: none;
  color: #9c1018;
}
#content {
  display: block;
  width: 100%;
  min-height: 500px;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  color: white;
  display: inline;
}
.contenttext {
  text-align: justify;
  color: white;
}.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: rgb(0, 255, 200);
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}    </style>
  </head>
  <body>
    <div class="container">
      <div class="banner">LEXICAL</div>
      <div class="menu">
        <div class="menuitem"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="product.html">Products</a></div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitemselected"><a href="contactus.html">Contact Us</a></div>
      </div>
      <hr>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us</h1><br><br>
          <h1>Address:</h1>
          <div class="contenttext">
            LEXICAL Private Limited ,Chennai-600 028
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Mr.gows(MARKETING MANAGER):8220156869<br><br>
              Mr.bhaskar(OPERATION MANAGER):9865432145<br><br>
              Mr.gopathi(OFFICE MANAGER):6384569585
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Sales:Lexicalprivatelimited@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 LEXICAL Limited, Developed by praveen s
      </div>
    </div>
  </body>
</html>
```
People.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>LEXICAL</title>
    <style>
      * {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-image: url("ss.jpg");
  background-size: cover;
 
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px rgb(0, 51, 255);
  background-color: rgb(129, 173, 255);
}
.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-weight: bold;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: whitesmoke;
}
.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: black;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}
.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}
.menuitem a {
  text-decoration: none;
  color: #9c1018;
}
#content {
  display: block;
  width: 100%;
  min-height: 500px;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  color: white;
  display: inline;
}
.contenttext {
  text-align: justify;
  color: white;
}
.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: rgb(0, 255, 200);
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}    </style>
  </head>
  <body>
    <div class="container">
      <div class="banner">LEXICAL</div>
      <div class="menu">
        <div class="menuitem"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="product.html">Products</a></div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitemselected"><a href="contactus.html">Contact Us</a></div>
      </div>
      <hr>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us</h1><br><br>
          <h1>Address:</h1>
          <div class="contenttext">
            LEXICAL Private Limited ,Chennai-600 028
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Mr.gows(MARKETING MANAGER):8220156869<br><br>
              Mr.bhaskar(OPERATION MANAGER):9865432145<br><br>
              Mr.gopathi(OFFICE MANAGER):6384569585
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Sales:Lexicalprivatelimited@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 LEXICAL Limited, Developed by praveen s
      </div>
    </div>
  </body>
</html>
```
Product.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>LEXICAL</title>
    <style>
      * {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
background-image: url("ss.jpg");
background-size: cover;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  bottom: 100px;
  box-shadow: 15px 15px 8px gray;
  background-color: rgb(136, 219, 255);
}
.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:green;
  text-align: center;
  padding-top: 20px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}
.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color:aquamarine;
}
.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: black;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}
.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-weight: bold;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: whitesmoke;
}
.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: rgb(5, 201, 37);
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}    </style>
  </head>
  <body>
    <div class="container">
      <div class="banner">LEXICAL</div>
      <div class="menu">
        <div class="menuitem"><a href="home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="product.html">Products</a>
        </div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRjg7XLRNypFgPxctEeC22iejUzaA-9E6uE-A&usqp=CAU" alt="product image">
                  </div>
                  <div class="itemname">FOOTBALL EVO</div>
                  <div class="itemprice">Price: Rs.7,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT3mL825i9sgv56UeoByzlOtSQdwDFhmS2Z2w&usqp=CAU"  alt="product image">
                  </div>
                  <div class="itemname">CRICKET CRACKS</div>
                  <div class="itemprice">Price: Rs.8,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 Limited, Developed by praveen s
      </div>
    </div>
  </body>
</html>
```
## OUTPUT:
### Home Page:
![iu](home.png)
### Contact Page:
![output](contactus.png)
### People:
![dd](people.png)
### Product :
![dd](product.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
