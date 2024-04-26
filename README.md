# Ex.06 Book Front Cover Page Design
## Date:

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
    <title>Book Cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(cyber.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(255, 240, 242);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:cornflowerblue;
            top:270px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:azure;
            font-family: 'Times New Roman', Times, serif;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            
        }
        .pub{
            color:azure;
            font-size: medium;
            position: relative;
            top:235px;
            left:330px;
        }
        .ed{
            color:azure;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:190px;
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                AI&DS/ML
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>DATA ODYSSEY</h1></div>
                <h2 style="color: aliceblue;">>Navigating the Seas of Information<</h2>
            
            <div class="subtitle">
                 Discovering the Power Of Data: <br>
                 A Tale of Science and AI
            </div>
<br><br>
           
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>ASHWINA K N</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Revised Edition</b>
            </div>
        </div>
        </body>
        

</html>
```


## OUTPUT:

![EX-6 1](https://github.com/Ashwinakn/cover/assets/152128332/daf9651f-a83d-4c97-968f-6b58547f179d)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
