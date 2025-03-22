# Ex.06 Book Front Cover Page Design

## To develop a website to display the cover page design of a book
## Design Steps:
Step 1:

Create a new Django project and app.

Step 2:

Create a static file directory and mention the changes in settings.

Step 3:

Make a new folder templates inside your app and create a html and map them using views and url.

Step 4:

Write down the code for book cover using HTML and CSS.

Step 5:

Add images and other contents using CSS record a screenshot of it.

## Code:
HTML:
```
{% load static %}

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML5 and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>Third Edition</h3>
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>Ben Frain</span>
                    <span id="end"><u>Packt></u></span>
                </div>
            </footer>
    </section>
    </body>
</html>
```
## CSS:
```
body{
    color:rgb(255, 255, 255);
    font-family: Helvetica, sans-serif;
    background-color: #333
}

.book{
    width: 726px;
    height:891px;
    background-color:rgb(0, 0, 0);
    margin:auto;
    position: relative;
    background-image: url('https://th.bing.com/th/id/R.671f161d141466cdcf83db28cb0f3a9c?rik=chK%2bVFNfy9d5yQ&riu=http%3a%2f%2fwww.textronic.com%2fblog%2fwp-content%2fuploads%2f2017%2f10%2fJARVIS.png&ehk=ZeD47puFibIuEgnTFLJ0EvR0pvMX2F4jcL4rRn2y4EU%3d&risl=1&pid=ImgRaw&r=0');
    background-repeat: no-repeat;
    background-size:606px;
    background-position: bottom 150px center;
}
h1{
    font-size:70px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: x-large;
    color: #f47027;
}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#top{
    border-bottom:2px solid #f47027;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 0px;
    border-top:2px solid #f47027;
    padding-top:10px;
    width:726px;
}
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:60px;
  }
```
## output:
![image](https://github.com/moulidharyadav/cover/assets/147078316/84000456-1d94-4210-b0f5-5dbd67f68b60)


## Result:

Successfully designed a website to display the cover page of the book "Responsive Web Design with HTML5 and CSS".
