# Ex.05 Book Front Cover Page Design
## Date:22-5-26

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

Bookcover.html
```
<!DOCTYPE html>
<html>
<head>
<title>Book Cover</title>

<style>

body{
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    background:lightgray;
    font-family:Arial;
}

.book{
    width:430px;
    height:620px;

    padding:20px;

    border:4px solid black;
    border-radius:15px;

    background-image:url("C:/Users/Marliya Banu/EX 5 BOOK COVER/cover/bookcover/bookapp/static/background.jpeg");

    background-size:cover;
    background-position:center;

    position:relative;

    box-shadow:0 0 0 4px white inset;
}
h1{
    color:black;
    font-size:40px;
    margin-bottom:10px;
}

.line{
    height:2px;
    background:black;
    margin-bottom:20px;
}



.content{
    font-size:13px;
    line-height:1.8;
    text-align:justify;
    color:black;
}

.highlight{
    background:yellow;
    font-weight:bold;
}



.quote{
    margin-top:20px;

    background:white;

    padding:15px;

    border-left:5px solid black;

    border-radius:8px;

    text-align:center;

    font-style:italic;

    color:black;

    font-size:16px;
}



.author{
    margin-top:30px;
    background:white;
    padding:8px;
    border-radius:5px;
    display:flex;
    gap:10px;
    width:400px;
    align-items:center;
}



.author img{
    width:90px;
    height:100px;

    border-radius:5px;

    object-fit:cover;
}




.author h5{
    margin:0;
    padding:0;
    font-size:14px;
    font-weight:600;
    color:black;
    line-height:1.2;
}
.author p{
    margin-top:5px;
    margin-bottom:0;
    font-size:13px;
    line-height:1.5;
    color:black;
}


.footer{
    position:absolute;
    bottom:5px;
    left:20px;
    right:20px;
    background:black;
    color:white;
    padding:15px;
    border-radius:10px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.price{
    color:yellow;
    font-size:25px;
    font-weight:bold;
}

</style>
</head>

<body>

<div class="book">

<h1>About the Book</h1>

<div class="line"></div>

<div class="content">

This book
<span class="highlight">
"Fundamentals of Web Application Development"
</span>

provides an engaging journey through the art and science of web design.
It explores how creativity meets technology to craft visually appealing
and user-friendly websites. Readers will learn essential design principles,
layout techniques, responsive practices, and the importance of user experience
that transforms ideas into digital reality.

</div>

<div class="quote">

"Design is not just what it looks like and feels like —
design is how it works on the web."

</div>

<div class="author">

<img src="C:/Users/Marliya Banu/EX 5 BOOK COVER/cover/bookcover/bookapp/static/marli.jpeg">

<div>

<h5>B MARLIYA BANU</h5>
<p>
B Marliya Banu is a passionate learner and creative thinker
interested in web development and modern web technologies.
She inspires students through innovative ideas and professional designs.
</p>

</div>

</div>

<div class="footer">

<div>
<b>SEC Publishers</b><br>
Printed in India
</div>

<div>
Price: <span class="price">₹399</span>
</div>

</div>

</div>

</body>
</html>
```

## OUTPUT:
![Book Cover](C:\Users\Marliya Banu\EX 5 BOOK COVER\cover\bookcover\bookapp\static\output.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
