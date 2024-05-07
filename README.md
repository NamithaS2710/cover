# Ex.06 Book Front Cover Page Design
## Date:

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
<!DOCTYPE html>
<html>
<style>
    .bookpage{
        width: 400px;
        height: 600px;
        color:rgb(14, 14, 15);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(/static/photucover.jpg);
        background-size: cover;
    }
        
    
    .futuristic{
        color: rgb(10, 10, 10);
    
    }
    
    
    .hrstyle{
        width:100px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: rgb(21, 21, 20);
        top:160px;
        
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 60px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:175px;
        
    }
    .pub{
        font-size: medium;
        position: relative;
        top:135px;
        left:330px;
    }
    .ed{
        color: black;
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:80px;
    
    }
    .subtitle{
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:70px;
    }
    .mypic{
        position: relative;
        top: 210px;
        left: 300px;
        width: 100px;
        height: 150px;
        background-size: cover;
        
    }
    </style>
    <title>Book Cover Page</title>
    </head>
    <body>
    <div class="bookpage">
        <div class="futuristic">
            AN EMPTY SPACE
        </div>
        <div class="hrstyle">
            <hr style="color: yellow;">
        </div>
        <div class="booktitle">
            <h1>SPINGy </h1></div>
        <div class="subtitle">
            
The Spring Decisions...
        </div>
        <div class="mypic">
            <img src="/static/photu.png" width="110" height="110" alt="">
        </div>
        <div class="id">
            <hr style="color: goldenrod;">
        </div>
        <div class="author">
           <p><b>Namitha.S</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Exclusive Edition</b>
        </div>
    </div>
    </body>
</html>
```
## OUTPUT:
![Screenshot 2024-05-07 092514](https://github.com/NamithaS2710/cover/assets/133190822/1bb9979a-8950-4d59-8f43-9c8b5f664e20)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
