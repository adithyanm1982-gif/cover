# Ex.06 Book Front Cover Page Design
## Date: 15/12/25
## Name: ADITHYA NM
## Register No: 25011586

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
book.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Book Front Cover</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #e6f2ff; /* Pleasant light blue */
            font-family: "Segoe UI", Arial, sans-serif;
        }

        .book-cover {
            width: 420px;
            height: 600px;
            background-color: #1f4fd8; /* Normal blue */
            color: white;
            padding: 30px;
            box-sizing: border-box;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.25);
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        .title {
            font-size: 30px;
            font-weight: bold;
            line-height: 1.3;
            margin-top: 30px;
            margin-bottom: 15px;
        }

        .author {
            font-size: 18px;
            font-weight: 500;
            letter-spacing: 0.5px;
            margin-bottom: 25px;
        }

        .image-section {
            width: 240px;
            height: 260px;
            border: 3px solid white;
            border-radius: 8px;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: auto;
            background-color: rgba(255,255,255,0.08);
        }

        .image-section img {
            max-width: 100%;
            max-height: 100%;
            border-radius: 4px;
        }

        .footer {
            font-size: 12px;
            opacity: 0.85;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="book-cover">

        <div class="title">
            The Art of Computer Programming
        </div>

        <div class="author">
            by Donald E. Knuth
        </div>

        <div class="image-section">
            <!-- Paste your image file name here -->
            <img src="adithyanm/bookapp/static/Donald E.Knuth.jpg" alt="Donald E. Knuth">
        </div>

        <div class="footer">
            Book Cover Design
        </div>

    </div>

</body>
</html>

```


## OUTPUT:
<img width="1919" height="968" alt="Cover Image" src="https://github.com/user-attachments/assets/61af4de9-0920-425d-9521-09e8507a2e84" />



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
