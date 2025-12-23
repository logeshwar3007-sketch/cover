# Ex.06 Book Front Cover Page Design
## Date:20/12/2025
## ref no:25014493

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
~~~
book.hmtl
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Web Development Book Cover</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #f2f2f2;
            font-family: Arial, Helvetica, sans-serif;
        }

        .book-cover {
            width: 400px;
            height: 600px;
            background: linear-gradient(180deg, #e53935, #ff3d3d);
            color: rgb(249, 245, 6);
            padding: 30px;
            box-sizing: border-box;
            position: relative;
        }

        .publisher {
            font-size: 14px;
            font-weight: bold;
            border-bottom: 2px solid white;
            display: inline-block;
            padding-bottom: 4px;
            margin-bottom: 40px;
        }

        .title {
            font-size: 36px;
            font-weight: bold;
            line-height: 1.3;
            margin-bottom: 20px;
        }

        .subtitle {
            font-size: 18px;
            opacity: 0.9;
            margin-bottom: 150px;
        }

        .edition {
            font-size: 16px;
            font-weight: bold;
            margin-bottom: 15px;
        }

        /* Image container */
        .author-image {
            width: 120px;
            height: 150px;
            background: white;
            padding: 5px;
            position: absolute;
            bottom: 90px;
            right: 30px;
            box-sizing: border-box;
        }

        .author-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .footer {
            position: absolute;
            bottom: 20px;
            width: calc(100% - 60px);
            display: flex;
            justify-content: space-between;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="publisher">SEC INSIGHT</div>

        <div class="title">
            Web Development:<br>
            The Complete<br>
            Reference
        </div>

        <div class="subtitle">
            with Django and Bootstrap Insights
        </div>

        <div class="edition">Extended Edition</div>

        
        <div class="author-image">
            <img src="logan .jpg" alt="Author Image">
        </div>

        <div class="footer">
            <div>Logan S</div>
            <div>SEC</div>
        </div>
    </div>

</body>
</html>
~~~

## OUTPUT:
<img width="1918" height="973" alt="image" src="https://github.com/user-attachments/assets/ce162851-fd6c-49e9-8386-5c9c31f89ccc" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
