# Ex-06-Book-Cover-Design

## AIM:
To design a book-cover-design using HTML and CSS.

## DESIGN PROCEDURE:
## STEP 1:
Start define the document type as HTML.

## STEP 2:
Open the HTML structure with necessary head and body sections.In the head section ,set the title as Book Coverpage and define the styles for the bookcover.Use the CSS styles in the code.The styles include:

background-color,

background-image,

background-position,

background-repeat,

padding,

font-size,

font-family,

background-size,

color,

line-height.

## STEP 3:
In the body section ,create a division with the text with respective to the headings:

"EXPERT INSIGHT"

"Web Alchemy: Unleashing the Power of HTML5 and CSS"

"Developing the  responsive websites using the latest HTML5 and CSS"

"EXTENDED EDITION"

"SAI GANESH DEPURU"

"SEC>"

## STEP 4:
Close the HTML structure.

## CODE:
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
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(https://wallpapercave.com/wp/wp2042122.jpg);
            background-size :cover;
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
            color:white;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: "Sans-Serif";
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            color:
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            color:white;
            top:155px;
            left:330px;
        }
        .edition{
            color:cyan;
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
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>"Web Alchemy: Unleashing the Power of HTML5 and CSS"
                </h1>
            </div>
            <div class="subtitle">
                Developing the  responsive websites using the latest HTML5 and CSS 
            </div>
            <div class="photo">
                <img src="C:\Users\admin\Documents\My Photo.jpg" width="130" height="145"alt="">
            </div>
            <div class="id">
                <hr style="color:red;">
            </div>
            <div class="author">
               <p><b>SAI GANESH DEPURU</b></p>
            </div>
            <div class="publisher">
                SEC>
            </div>
            <div class="edition">
                <b>EXTENDED EDITION</b>
            </div>
            
        </div>
    </body>
</html>
```
## OUTPUT:
![image](https://github.com/saiganesh2006/Ex-06-Book-Cover-Design/assets/145742342/ed2a2374-17d7-4dd3-bb65-cd27ff53732a)

## RESULT:
Thus the book-cover-design has been successfully created using HTML and CSS.


