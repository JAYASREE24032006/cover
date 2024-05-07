# Ex.06 -  Book Front Cover Page Design
## Date: 12.04.2024

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

<head>
    <title>BOOK COVER</title>
    <style>
        .bookcover{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(LA1.png);
            background-size: cover;
        }
            
        
        .head{
            color:rgb(18, 231, 135);
        
        }
        
        
        .style{
            width:100px;
        }
        .authorname{
        
            display: inline;
            position: relative;
            color:rgb(208, 22, 22);
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .title{
            color:rgb(89, 17, 17);
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .last{
            color:rgb(14, 17, 217);
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .end{
            color:rgba(9, 67, 214, 0.94);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:rgb(17, 52, 207);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
            text-align: center;
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookcover">
            <div class="style">
                <hr style="color:rgb(211, 120, 120)">
            </div>
            <div class="title">
                <h1>Data Structures and Algorithms with JavaScript</h1></div>
            <div class="subtitle">
                 <P><B>Bringing Classic Computing Approaches to the Web</B></P>
            </div>
            <div class="photo">
                <img src="NA.jpg" width="90" height="120">
            </div>
            <div class="authorname">
               <p><b>JAYASREE R </b></p>
            </div>
            <div class="end">
                <b>REVISED EDITION</b>
            </div>
        </div>
        </body>
```


## OUTPUT:
![Screenshot 2024-05-07 094316](https://github.com/JAYASREE24032006/cover/assets/144360800/6b04ecf2-12d2-44fb-bf20-08841f3a1945)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
