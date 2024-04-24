# Ex.06 Book Front Cover Page Design
## Date:20/04/24

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
        .bookcover {
            width: 400px;
            height: 600px;
            color: black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: Arial, sans-serif; /* corrected font-family declaration */
            background-image: url(back.jpg);
            background-size: cover;
        }

        .head {
            color: rgb(34, 102, 157);

        }

        .style {
            width: 100px;
        }

        .authorname {
            display: inline;
            position: relative;
            color: rgb(136, 72, 49);
            top: 190px;
            font-family: Georgia;
            font-size: medium;
        }

        .title {
            color: rgb(89, 17, 17);
            font-family: Arial, sans-serif; /* fallback font */
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;

        }

        .line {
            width: 400px;
            position: relative;
            top: 180px;
        }

        .last {
            color: rgb(154, 90, 90);
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }

        .end {
            color: rgba(7, 7, 7, 0.94);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 85px;

        }

        .subtitle {
            color: rgb(0, 0, 0);
            font-family: Arial, sans-serif; /* fallback font */
            font-size: large;
            position: relative;
            top: 40px;
        }

        .photo {
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px; /* Adjust the size here */
            height: 100px; /* Adjust the size here */
        }
    </style>
</head>

<body>
    <div class="bookcover">
        <div class="head">
            Artifical intelleigence
        </div>
        <div class="style">
            <hr style="color:rgb(211, 120, 120)">
        </div>
        <div class="title">
            <h1>Data Science</h1>
        </div>
        <div class="subtitle">
            Data Analytics
        </div>
        <div class="subtitle">
            Best seller of 2024
        </div>

        <div class="photo">
            <img src="me.jpg" width="90" height="100">
        </div>
        <div class="line">
            <hr style="color:rgba(81, 13, 13, 0.555)">
        </div>
        <div class="authorname">
            <p><b>Naveen kumar V</b></p>
        </div>
        <div class="last">
            SEC
        </div>
        <div class="end">
            <b>NEW EDITION</b>
        </div>
    </div>
</body>

</html>
```

## OUTPUT:
![alt text](back.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
