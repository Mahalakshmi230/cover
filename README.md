# Ex.06 Book Front Cover Page Design
## Date:15.4.2024

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
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style type="text/css">
            .bookcover {
                width: 400px;
                height: 640px;
                color: black;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                background-image: url(cover.jpeg  );
                background-size: cover;
            }
            .insight {
                color: (221, 39, 39);
            }
            .hr1 {
                width: 130px;
            }
            .h1 {
                font-size: larger;
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                position: relative;
                top: 30px;
            }
            .para {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                top: 40px;  
            }
            .edition {
                font-size: large;
                font-family: Arial, Helvetica, sans-serif;
                color:black;
                top: 90px;
                position: relative;
            }
            .pic {
                position: relative;
                top: 150px;
                left: 250px;
                width: 100px;
                height: 100px;
                background-size: cover;
            }
            .hr2 {
                position: relative;
                width: 400px;
                top: 200px;
            }
            .name {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                display: inline;
                position: relative;
                color:black(94, 218, 32);
                top: 210px;
            }
            .pub {
                font-size: large;
                position: relative;
                top: 180px;
                left: 330px;
            }
        </style>
        <title> Book Front Cover Page  </title>
    </head>
    <body>
        <div class="bookcover">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hr1">
                <hr>
            </div>
            <div class="h1">
                <h1> Building Web Apps for Everyone </h1>
            </div>
            <div class="para">
                <p> The opportunity to use the latest technologies of the web development </p>
            </div>
            <div class="pic">
                <img src="Screenshot_16-4-2024_181854_.jpeg" width="130" height="145" alt="">
            </div>
            <div class="hr2">
                <hr>
            </div>
            <div class="name">
                <p><b>MAHALAKSHMI R</b></p>
            </div>
            <div class="pub">
                <b> SEC </b>
            </div>
            <div class="edition">
                <b> Third Edition </b>
            </div>
        </div>
    </body>
</html>
```
## OUTPUT:
![Screenshot 2024-04-16 201249](https://github.com/Mahalakshmi230/cover/assets/149365324/d54d6fca-92d0-42a3-aaf4-fa0ca6f0b30f)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
