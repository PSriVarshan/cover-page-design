# cover-page-design

## AIM:

To develop a website to display the cover page design of a book


## Design Steps:


### Step 1:

Create a new Django project and app.

### Step 2:

Create a static file directory and mention the changes in settings.

### Step 3:

Make a new folder templates inside your app and create a html and map them using views and url.

### Step 4:

Write down the code for book cover using HTML and CSS

### Step 5:

Add images and other contents using CSS record a screenshot of it


## Code:


```html

<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('/static/images/cover.jpg');
            background-size: cover;
        }
        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color:lightblue;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:rgb(0, 0, 0);
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
        .photo{
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
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: white;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="/static/images/h1.jpg" height="130" width="145">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>Tristan Tate</b></p>
            </div>
            <div class="publisher">
                Packt>
            </div>
            <div class="edition">
                <b>Third Edition</b>
            </div>
            
        </div>
    </body>
</html>
```

## Output:

### Server :

![image](https://github.com/PSriVarshan/cover-page-design/assets/114944059/e6da252c-8b79-4652-918d-50fa96b31bf4)


### Cover Page  :

![image](https://github.com/PSriVarshan/cover-page-design/assets/114944059/c2939040-867f-4ea8-868a-f74a973f2117)


## Result:

Successfully designed a website to display the cover page of the book Responsive Web Design with HTML5 and CSS.
