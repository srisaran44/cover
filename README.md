# Ex.06 Book Front Cover Page Design
## Date:08\10\25
## Name: SRI SARAN J
## Ref No: 25015592

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
<!DOCTYPE html>
<html>
<head>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color : black
      background-size: cover;
      background-position: center;
      color: black;
      background-color: orange;
    }
    .cover {
      width: 700px;
      height: 1000px;
      margin: 50px auto;
      padding: 30px;
      position: relative;
      background: rgba(255, 250, 240, 0.9); 
      border: 5px solid red; 
      border-radius: 2%;
      background-image:url(bg.jpg);
    }
    .top {
      font-size: 40px;
      font-weight: bold;
      color: blue;
      text-align: left;
      letter-spacing: 2px;
    }
    .title {
      font-size: 60px;
      font-weight: bold;
      text-align: center;
      margin-top: 80px;
      color: rgb(138, 3, 3);
      font-family: 'Times New Roman', serif;
    }
    .subtitle {
      font-size: 40px;
      text-align: center;
      margin-top: 30px;
      font-style: italic;
      color: lime;
    }
    .special {
      font-size: 40px;
      font-weight: bold;
      margin-top: 480px;
      color: white;
      text-align: left;
    }
    .author {
      font-size: 30px;
      font-weight: bold;
      color: black;
      margin-top: 25px;
      text-align: left;
    }
    .sec {
      position: absolute;
      bottom: 30px;
      right: 20px;
      font-size: 18px;
      color: white;
    }
    .photo {
      width: 200px;
      height: 260px;
      position: absolute;
      bottom: 60px;
      right: 100px;
      border-radius: 8px;
      border: 2px dotted yellow;
      box-shadow: 0 0 10px black
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="top">SEC Insights</div>
    
    <div class="title">
      SHAPING THE FUTURE<br>
        WITH TECHNOLOGY
    </div>
    
    <div class="subtitle">
      innovation is endless and <br>
      innovation shapes tomorrow
    </div>
    
    <div class="special">SPECIAL EDITION</div>
    
    <img src="me.jpg" class="photo" alt="Author Photo">
    
    <div class="author">srisaran(25015592)
    </div>
    
    <div class="sec">SEC</div>
  </div>
</body>
</html>
style.css
body{
    background-color: #000000;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-style: oblique;
    color:rgba(255, 255, 255, 0.853);
}
.cover{
    background-image:url(spider.jpg);  
    background-clip: border-box;
    background-position-x: right;
    background-size: cover;  
    height: 725px;
    width: 500px;
    position: relative;
    left: 500px;
}
.main{
    margin: auto;
    border: solid 8px rgb(244, 236, 236);
}
.title{
    font-size: 12px;
    color: rgb(255, 255, 255);
    font-weight: 800;
    position: relative;
    top: 20px;
    left: 10px;
    width: 140px;
}
.content{
    font-size: 35px;
    text-align: center;
    position: relative;
    top: 0px;
    color:rgba(0, 0, 0, 0.853);
    font-weight: 800;
    
}
.subtitle{
    position: relative;
    left: 10px;
    font-size:18px;
    
}
.image{
    width: 150px; 
    height:190px;      
    position: relative;
    top: 70px;
    left:300px;
    border: 2px solid rgb(255, 254, 254);
    background: rgb(63, 161, 219);
    overflow: hidden;   
}
.image img{
    width: 100%;
    height: 100%;
    color:rgb(255, 255, 255);
    object-fit: cover;
}
.edition{
    position: relative;
    top: 50px;
    left: 1px;
    font-weight: bolder;
}
.author{
    position: relative;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    top: 45px;
    left:20px;
    font-size: 18px;
    color:rgba(229, 38, 38, 0.853);
}
.sub-bottom{
    font-family: Arial, Helvetica, sans-serif;
    position: relative;
    bottom:5px;
    left:380px;
    font-size: 15px;
    color:rgba(218, 63, 63, 0.853);
}

.name{
    text-align: center;
    position: relative;
    right:50px;
    color:rgb(26, 198, 198);
}
```

## OUTPUT:
<img width="1920" height="1020" alt="Book Cover and 3 more pages - Personal - Microsoft​ Edge 18-10-2025 11_51_43" src="https://github.com/user-attachments/assets/fad7046c-f3e1-45e5-a129-7cf4ca4d53f1" />



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
