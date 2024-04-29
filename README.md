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
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('bookcover.png');
            background-size: cover;
        }

        .insight{
            color:rgb(13, 6, 6) ;

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: blue;
            display: inline;
            position: relative;
            color: rgb(42, 6, 245);
            top: 200px;

            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 50px;
        }

        .id{
            width: 400px;
            position: relative;
            top: 180px;

        }

        .pub{
            font-size: large;
            position: relative;
            top: 100px;
            left: 300px;
        }
        .ed{
            color: blue;
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 120px;

        }
        .subtitle{
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 50px;
        }
        .mypic{
            position: relative;
            top: 290px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="EXPERT INSIGHT">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(10, 10, 10);">
            </div>
            <div class="booktitle">
                <h1>FULL STACK WEB DEVELOPMENT</h1>
            </div>
            <div class="subtitle">
              the comprehensive guide
            </div>
            
            <div class="id">
                <hr style="color:rgb(10, 10, 10);">
            </div>
            <div class="author">
                <p><b>PRIYADHARSHINI</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Third Edition</b>
            </div>
        </div>
    </body>
</html>
```
## OUTPUT:
![image](https://github.com/AmirthaRoopaS/cover/assets/143496311/9f9136b5-c77f-443e-9acb-034be21ed8de)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
