# Ex.06 Book Front Cover Page Design
## Date:04.10.2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
cover.html

<html>
<head>
<meta name="viewport"
content ="width=device-width, initial-scale=1.0">
<title>Book Cover Page</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="bookpage">

<div class="insight">
SEC INSIGHT
</div>
<div class="hrstyle">
<hr style="color: WHITE;">
</div>
<div class="booktitle">
<h1>ARTIFICIAL INTELLIGENCE</h1>
</div>
<div class="subtitle">
Revolutionizing Machines with Human-like Intelligence
</div>
<div class="mypic">
<img src="jeevitha k.jpg" width="130" height="145" alt="jeevitha k.jpg">
</div>
<div class="author">
<p><b>Jeevitha K</b></p>
</div>
<div class="pub">
SEC
</div>
<div class="id">
    <hr style="color: white;">

</div>
<div class="ed">
<b>SPECIAL RELEASE</b>
</div>
</div>
</body>
</html>



style.css

.bookpage{
width: 400px;
height: 600px;
color: white;
margin-left: auto;
margin-right: auto;
font-family: 'Franklin Gothic Medium', 'Arial Narrow', 'Arial', sans-serif;
background-image: url(back2.jpg);
background-size: cover;
padding: 10px;
border: 7px solid rgb(137, 128, 128);
border-radius: 5px;

}
.insight{
color: white;

}

.hrstyle{
width: 23%;

}

.author{

display: inline;
position: relative;
color: white;
top: 245px;
font-family: Georgia;
font-size: medium;

}

.booktitle{

font-family: 'Courier New', Courier, monospace;
font-size: larger;
text-align: center;
position: relative;
top: 30px;

}

.id{
width: 400px;
position: relative;
top: 175px;



}

.pub{
font-size: medium;
position: relative;
top: 210px;
left: 340px;

}
.ed{
color: white;
font-size: medium;
font-family: Verdana;
position: relative;
top: 140px;

}

.subtitle{
font-family: Tahoma;
font-size: large;
position: relative;
top: 40px;

}
.mypic{
position: relative;
top: 190px;
left: 260px;
width: 95px;
height: 100px;
background-size: cover;
}



```


## OUTPUT:
![alt text](bookcover.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
