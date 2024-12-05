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
<html>
    <head>
        <title>my book</title>
        <style>
            .main{
                position: relative;
                margin: center;
                margin-left: 500;
                background-repeat: no-repeat;
                height: 750px;
                width:550px;
                background-image: url(book.jpg);
                
            }
            .heading{
                
                position: absolute;
                top: 150px;
                left: 50;
                font-size: 45;
                font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            }
            .ver{
                position: absolute;
                right: 20;
                font-family:cursive;
                font-size: 12;
            }
            .year{
                position: absolute;
                top: 20px;
                right: 20;
                font-size: 10;
                font-family: serif;
            }
            .name{
                position:absolute;
                bottom: 20px;
                left:20
            }
            .me{
                position: absolute;
                height: 130;
                right:10;
                bottom:45;
            }

        </style>
    </head>
    
    <body>
        <div class="main">
            
            <h1 class="heading">FULL STACK <BR>DEVELOPMENT</h1>
            <h6 class="ver">YEAR OF PUBLISH</h6>
            <h6 class="year">2024</h6>
            <h5 class="name">JOHN PALL M</h5>
            <img class="me" src="WhatsApp Image 2024-12-05 at 20.07.37_171c1d01.jpg">
                        
            
            
        </div>
        
    </body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (46).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
