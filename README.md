# EXP 09 - BIRTHDAY CARD

## AIM:

To create a Birthday card using HTML and CSS

## ALGORITHM:

1. Set up the basic structure of your HTML document and include the CSS stylesheet.

2. Design the layout of your birthday card using HTML elements such as < div >, < h1 >, < p >, < img >, and < span >. 

3. Add a container < div > to hold the entire birthday card content.
  
4. Use paragraph tag to disply the personalised greeting. Add an image element to display a birthday-themed image.

## CODE:

### BIRTHDAY.HTML
```
<!DOCTYPE html>
<html>
    <head>
        <title>Wishes!!</title>
        <link rel="icon" href="./sticker1.png" type="icon" />
    <style>
        .animation_1{
            width: 90px;
            height: 100px;
            background-image: url(sticker_2.jpg);
            background-size: 100% 100%;
            position: relative;
            animation: mymove 4s infinite;
        }
        @keyframes mymove {
            from {left: 0px;}
            to {left: 650px;}
        }
        .box{
            width: 600px;
            height: 900px;
            padding-top: 50px;
            padding-left: 120px;
            background-size: 100% 100%;
            background-image: url(Wallpaper_2.png);
        }
        .font_style{
            font-family: Georgia, 'Times New Roman', Times, serif;
            color: aliceblue;
            
        }
    </style>
    </head>
    <div class="animation_1"></div>
    <div class="box">
        <body style="padding-left: 450px; padding-top: 50px;padding-bottom: 50px; background-image: url(wallpaper.png);background-size: 100% 100%; border: 5px solid black;">
        <div class="font_style">
            <br><br><br><br><br><br><br><br>
            <p style="font-size: 48px; color: rgb(255, 183, 89);">&ensp;HAPPY BIRTHDAY</p> 
            <p style="font-size: 30px; color: rgb(255, 255, 163);">&ensp;Wishing you a fantastic birthday<br><br>
                &emsp;and a wonderful year aheaad!!!</p>
            <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; font-size: 30px; color:rgb(201, 149, 71)">&emsp;CHEERS TO YOUR PERSONAL<br><br>&emsp;&emsp;&emsp;&emsp;&emsp; NEW YEAR!
                <br><br>&emsp;&emsp;&emsp;&ensp;SO LETS LIVE IT UP<br><br>&emsp;&emsp;&emsp;&ensp;<img src="https://bestbirthdayimages.com/wp-content/uploads/2018/01/Funny-Birthday-WIshes.jpg" height="200px" width="250px"></p>
        </div>
    </body>
    </div>
</html>
```
## OUTPUT:
![image](https://github.com/gpavithra673/Exp_09_Create-a-Birthday-card-using-HTML-and-CSS/assets/93427264/b761f0fe-e593-40e9-aa41-4d95b9773d0e)


## RESULT

So,  a birthday card is created using CSS and HTML.
