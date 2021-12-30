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
HOME PAGE.HTML:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>ASUNA Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ASUNA Private Limited </div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/Banner.jpg" alt="Image" />
          <div class="contenttext">
            Welcome to ASUNA Private Limited!
            ASUNA private limited helps you to purchase very good quality of iphones which are money worthy.
            The iPhone is a line of smartphones designed and marketed by Apple Inc. that use Apple's iOS mobile operating system. 
            The first-generation iPhone was announced by then-Apple CEO Steve Jobs on January 9, 2007. 
            Since then, Apple has annually released new iPhone models and iOS updates. 
            As of November 1, 2018, more than 2.2 billion iPhones had been sold.

            The iPhone has a user interface built around a multi-touch screen. 
            It connects to cellular networks or Wi-Fi, and can make calls, browse the web, take pictures, play music and 
            send and receive emails and text messages. Since the iPhone's launch further features have been added, including larger 
            screen sizes, shooting video, waterproofing, the ability to install third-party mobile apps through an app store, 
            and many accessibility features. Up to iPhone 8 and 8 Plus, iPhones used a layout with a single button on the front panel 
            that returns the user to the home screen.
            <br />
            We hope our company would help you in getting good products from Apple, 
            and we are very greatful to provide you this wondeful service.
            <ul>
              <li>Simple to search, easier to use</li>
              <li>Worthy produts</li>
              <li>Anywhere, anytime access</li> 
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 ASUNA Private Limited, Developed by Anusha R
      </div>
    </div>
  </body>
</html>
~~~
PRODUCT>HTML:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>ASUNA Private  Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ASUNA Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m1.jpg" alt="product image">
                  </div>
                  <div class="itemname">iPhone 11</div>
                  <div class="itemprice">Price:Rs.46120</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">iPhone 12</div>
                  <div class="itemprice">Price:Rs.65900</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">iPhone XR</div>
                  <div class="itemprice">Price: Rs.40999</div>
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/m4.jpg"  alt="product image">
                </div>
                <div class="itemname">iPhone SE</div>
                <div class="itemprice">Price: Rs.39900 </div>
            </div>

            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/m5.jpg"  alt="product image">
              </div>
              <div class="itemname">iPhone 13 Pro</div>
              <div class="itemprice">Price: Rs.119900</div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/m6.jpg"  alt="product image">
            </div>
            <div class="itemname">iPhone 13 mini</div>
            <div class="itemprice">Price: Rs.69900</div>
        </div>

        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/m7.jpg"  alt="product image">
          </div>
          <div class="itemname">iPhone 13 Pro Max</div>
          <div class="itemprice">Price: Rs.129900</div>
      </div>

      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/m8.jpg"  alt="product image">
        </div>
        <div class="itemname">iPhone 11</div>
        <div class="itemprice">Price: Rs.49900</div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/m9.jpg"  alt="product image">
      </div>
      <div class="itemname">iPhone 12</div>
      <div class="itemprice">Price: Rs.65900</div>
    </div>

    <div class="productitem"> 
       <div class="itemimage">
       <img src="/static/img/m10.jpg"  alt="product image">
       </div>
       <div class="itemname">iPhone 12 Pro</div>
       <div class="itemprice">Price: Rs.99900 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/m11.jpg"  alt="product image">
    </div>
       <div class="itemname">iPhone 12 series</div>
       <div class="itemprice">Price: Rs.114000</div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/m12.jpg"  alt="product image">
     </div>
        <div class="itemname">iPhone 12 Pro Max</div>
        <div class="itemprice">Price: Rs.12300</div>
      </div>
    </div>
  </div>        
  </div>
    <div class="footer">
      Copyright &#169; 2021 ASUNA Private Limited, Developed by Anusha R
    </div>
  </div>
 </body>
</html>
~~~
CONTACT.HTML:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>ASUNA Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/globee.png" type="image/x-icon" />
  </head>
  
  <body>
    <div class="container">
      <div class="banner">ASUNA Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      
        <div class="contact content">
           <h1>Our Contact Address</h1>  
        
          <div class="contacttext">
           Address: 13, Shanthi nagar, annanagar, Chennai - 6000101
           <br>Phone:7037648951
           <br>Email-address:asuna@gmail.com
          </div>
        </div>

     
<div class="footer">
  Copyright &#169; 2021 ASUNA Private Limited, Developed by Anusha 
</div>
</div>
</body>
</html>
~~~
PEOPLE.HTML:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>ASUNA PrivateLimited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ASUNA Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p1.jpg"  alt="product image">
      </div>
         <div class="itemname">HEAD of the company
           <br>
           (John Mendes)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p2.jpg"  alt="product image">
      </div>
         <div class="itemname">Manager
           <br>
           (Nickelson)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p3.jpg"  alt="product image">
      </div>
         <div class="itemname">Assistant class <br>(Ben Mark)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p4.jpg"  alt="product image">
      </div>
         <div class="itemname">Product Department Head <br> (Park Jenney)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p5.jpg"  alt="product image">
      </div>
         <div class="itemname">Deliver Department Head <br> (Zendey)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p6.jpg"  alt="product image">
      </div>
         <div class="itemname">Chennai Branch Head <br> (Beckkey)</div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 ASUNA Private Limited, Developed by Anusha R
      </div>
    </div>
  </body>
  </html>
  ~~~
  LAYOUT.CSS:
  ~~~
  * {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: rgb(0, 0, 0);
  color: #7953b6;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px rgb(54, 49, 49);
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/S5.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #850ba3;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #000000;
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
  color: #420fa0;
}

.menuitem a {
  text-decoration: none;
  color: #de3fe4;
}

.content {
  display: block;
  width: 100%;
  background-color: #000000;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: rgb(96, 11, 145);
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #4a0681;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #f34deb;
}
~~~
## OUTPUT:
![output](./images/s1.png)
![output](./images/s2.png)
![output](./images/s3.png)
![output](./images/s4.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
