# Ex.06 Book Front Cover Page Design
## Date: 20/10/2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(3, 252, 236);
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/Users/apple/Desktop/web/exp6/cover.jpg);
            background-size: cover;
        }
        .insight{
            color: rgb(7, 255, 243);
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display: inline;
            position: relative;
            color: rgb(1, 255, 221);
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: 19px;
            text-align: center;
            position: relative;
            top: 30px;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgb(0, 255, 247);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
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
            <div class="insight">EXPERT INSIGHT</div>
            <div class="hrstyle"><hr style="color: rgb(0, 87, 218);"></div>
            <div class="booktitle"><h1>Responsive Web Design with HTML5 and CSS</h1></div>
            <div class="subtitle">Develop future-proof responsive websites using the latest HTML5 and CSS techniques</div>
            <div class="mypic"><img src="/Users/apple/Desktop/web/exp6/ME.jpeg" width="130" height="145" alt=""></div>
            <div class="id"><hr style="color: rgb(0, 47, 255);"></div>
            <div class="author"><p><b>BY RICHARDSON A</b></p></div>
            <div class="pub">OPEN >>></div>
            <div class="ed"><b>Special Edition</b></div>
        </div>
    </bodY>
</html>

```
## OUTPUT:

![image](https://github.com/Richard01072002/cover/assets/141472248/11d272ff-d929-4092-a846-0047f77fb54e)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
