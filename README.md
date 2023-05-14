# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:
 
## Step 1:
Create a new Django project and app.
### Step 2:
Create a static file directory and mention the changes in settings.
### Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.
### Step 4:
Write down the code for book cover using HTML and CSS.
### Step 5:
Add images and other contents using CSS record a screenshot of it.

## Code:

cover.html code
~~~
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 500px;
            height: 650px;
            color:Trebuchet MS;
            margin-left: auto;
            margin-right: auto;
            padding: 25px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(bg.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:rgb(108, 18, 226);

        }
        
        .h1{
            font-weight: bold; 
        }
        
        .tophr{
            width:140px;
        }
        .author{
            color: rgb(108, 18, 226);
            display: inline;
            position: relative;
            color:rgb(108, 18, 226);
            top:210px;
            
            font-family:Trebuchet MS;
            font-size: medium;
        }
        .booktitle{
            font-family: Trebuchet MS;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }       
                   
        .publisher{
            font-size: medium;
            position: relative;
            top:180px;
            left:330px;
        }
        .edition{
            color:rgb(65, 5, 32);
            font-size: large;
            font-family:Trebuchet MS ;
            position:relative;
            top:67px;

        }
        .subtitle{
            font-family:Trebuchet MS;
            font-size: large;
            position: relative;
            top:40px;
            left:10px;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                <h2>A NOVEL</h2>
            </div>
            <div class="tophr">
                <hr style="color: black">
            </div>
            <div class="booktitle">
                <h1>IT ENDS WITH US</h1></div>
            <div class="subtitle">
                <h2 style="font-style: italic;font-weight: lighter;">Sometimes... <br> One Who Loves You <br>
                Is The One Who <br> Hurts You The Most...</h2>
            </div>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <div class="author">
               <p><b>COLLEEN HOOVER</b></p>
            </div>
            <div class="publisher">
                NEW YORK BESTSELLER
            </div>
            <div class="edition">
                <b>#1 BESTSELLING AUTHORS</b>
            </div>
            
        </div>
    </body>
</html>
~~~

## Output:
![Screenshot 2023-05-14 184956](https://github.com/surrey-78/cover-page-design/assets/119559366/72876c42-4231-4ffe-9c12-26acede217b1)


## Result:
Thus a website to display the cover page design of a book was successfully created.
