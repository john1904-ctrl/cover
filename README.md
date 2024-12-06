# Ex.06 Book Front Cover Page Design
## Date: 05/12/2024

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
    <title>my book</title>
    <style>
        .main {
            position: relative;
            margin: center;
            margin-left: 500px;
            background-repeat: no-repeat;
            height: 710px;
            width: 550px;
            background-image: url('book.jpg');
            border: 2px solid #000; 
        }
        .heading {
            position: absolute;
            top: 10px;
            left: 30px;
            font-size: 45px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .title {
            position: absolute;
            top: 120px;
            left: 30px;
            font-size: 30px;
        }
        .ver {
            position: absolute;
            left: 20px;
            font-family: cursive;
            font-size: 12px;
            bottom: 1px;
        }
        .vers {
            position: absolute;
            left: 20px;
            font-family: cursive;
            font-size: 12px;
            bottom: 15px;
        }
        .year {
            position: absolute;
            top: 20px;
            right: 20px;
            font-size: 10px;
            font-family: sans-serif;
        }
        .name {
            position: absolute;
            bottom: 20px;
            right: 20px;
            font-family: Arial, sans-serif;
            font-size: 14px;
            color: #000;
        }
        .me {
            position: absolute;
            height: 130px;
            right: 10px;
            bottom: 65px;
        }
        .mine {
            position: absolute;
            top: 600px; 
            left: 10px; 
            font-family: cursive;
            font-size: 12px;
            
          
        }
        .line {
            position: absolute;
            width: auto;
    
            height: 2px; 
            background-color: orangered;
            bottom: 130px;
        }
        .hr{
            position: absolute;
            width:100%; 
            height: 2px;
            background-color: rgb(255, 115, 0);
            bottom: 55px; 
        
  
        }
    </style>
</head>
<body>
    <div class="main">
        <h1 class="heading">FULL STACK <br> DEVELOPMENT</h1>
        <h4 class="title">TO LEARN HTML, CSS, JAVASCRIPT, REACT, SQL IN THIS BOOK</h4>
        
        <h5 class="mine">PRIME EDITION</h5>
        <h6 class="year">2024</h6>
        
        <img class="me" src="WhatsApp Image 2024-12-05 at 20.07.37_171c1d01.jpg" alt="Author Image">
        
        <h5 class="name">JOHN PALL M</h5>
        <h6 class="vers">Author</h6>
        <h6 class="ver">Tim Berners-Lee</h6>
        <hr class="hr">
    </div>
</body>
</html>

```


## OUTPUT:

![Screenshot (48)](https://github.com/user-attachments/assets/6ef8fa09-ce6c-420c-aa45-80fb2ab68af5)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
