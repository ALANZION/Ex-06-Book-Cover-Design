# Ex-06-Book-Cover-Design
## AIM:
To design a static web site for a book cover page.
## DESIGN STEPS:
## Step 1:

Create a new Django project and app.
## Step 2:

Create a static file directory and mention the changes in settings.
## Step 3:

Make a new folder templates inside your app and create a html and map them using views and url.
## Step 4:

Write down the code for book cover using HTML and CSS.
## Step 5:

Add images and other contents using CSS record a screenshot of it.

## CODE :
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #180909;
            color:rgb(255, 255, 255);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'BOLD', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/6.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:rgb(255, 255, 255);

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: rgb(255, 255, 255);
            display: inline;
            position: relative;
            color:rgb(173, 230, 197);
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
            color:rgb(85, 0, 255);
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
                <hr style="color: rgb(180, 13, 135);">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2023-12-21 083249.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(200, 255, 0);">
            </div>
            <div class="author">
               <p><b>ALAN ZION H</b></p>
            </div>
            <div class="publisher">
                Packt>
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
## OUTPUT:

![Book cover SS]![image](https://github.com/ALANZION/Ex-06-Book-Cover-Design/assets/145743064/599ead46-e9ea-4e3b-abf6-ffa5eab11f96)

