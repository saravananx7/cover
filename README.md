# Ex.05 Book Cover Page Design
## Date:15/12/25

## AIM:
To design a book back cover page using HTML and CSS.

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
        <title>Cascading Style Sheet</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <div class="book">
            <div class="h1">
            <h1>About the Book</h1>
            <hr>
            </div>
            <div class="cont">
                <p>This Book<span>  The evolution of computer science</span> spans from ancient calculation tools like the abacus and Babbage's mechanical Analytical Engine, through the hardware-focused "generations" (vacuum tubes to transistors to integrated circuits/microprocessors), leading to the digital age of personal computers, the internet, and modern focus on AI, machine learning, quantum computing, and data science, shifting from pure calculation to complex systems, software, and societal impact. </p>
            </div>
            <div class="quote">
            "Computer programming is an art, because it applies accumulated knowledge to the world, because it requires skill and ingenuity, and especially because it produces objects of beauty."
            </div>
            <div class="author">
                 <div class="author-img"></div>

                <div class="author-text">
                     <div class="name">SARAVANAN K</div>
                     <p>
                       Saravanan K. I am currently pursuing my engineering degree at Saveetha Engineering College, where I am building a strong foundation in technical knowledge and problem-solving skills. 

                     </p>
                </div>
            </div>
            <div class="footer">
                <div class="footer-left">
                    <strong>sec publishers</strong>
                    <br>
                    <div class="printed">printed in India</div>
                </div>
                <div class="price">Price= rs99/</div>
            </div>
        </div>
    </body>
</html>

body
{
    background: url('Screenshot 2025-12-15 231901.png') center / contain no-repeat fixed;
    min-height: 100vh;
    display: flex;
    justify-content: center;
}
.book
{
    padding-left: 700px;
    padding-right: 700px;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

.h1
{
    padding-top: 15px;
    font-style: Montserrat;
    color: rgb(123, 23, 210);
    padding-left: 20px;
}
.cont
{
    font-size: 17px;
    text-align: center;
    text-align: justify;
    padding-left: 15px;
    font-style:inherit
}
span
{
    background-color: yellow;
}
.quote
{
    margin: 10px 0;
    padding: 10px 10px;
    background: rgb(118, 185, 229);
    border-left: 6px solid rgb(15, 16, 13);
    font-style: italic;
}
.author-text 
{
    display: flex;
    flex-direction: column;
    font-size: 15px;
    
}

.author
{
    display: flex;
    gap: 9px;
    background: rgb(38, 92, 136);
    padding: 8px;
    border-radius: 8px;
    margin-top: 15px;
    text-align: justify;
    align-items: center;
}
.author-img 
{
    width: 400px;
    height: 100px;
    border-radius: 8px;
    background-image: url('Screenshot 2025-12-15 232501.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
.name 
{
    color: rgb(211, 8, 66);
    font-weight: bold;
    font-size: 15px;
}
.footer 
{
    margin-top: auto;
    background-color:rgb(48, 141, 170);
    color: rgb(67, 55, 43);
    padding: 5px 5px;
    border-radius: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.footer-left 
{
    display: flex;
    flex-direction: column;
}
.printed
{
    font-size: 14px;
}
.price 
{
    font-weight: bold;
    color: rgb(12, 12, 11);
    font-size: 18px;
}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-15 235101.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
