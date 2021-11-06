Hello everyone, You are welcome to Group 4 : 4xDevelopers Documentation/Guidelines

NOTE: Please read and read over again so as to assimilate the project structure and your contribution and if you don't understand
please reachout to Team Lead and Assistant Team Lead. Check their details below.

And before you start contributing check the design folder so the the prototype of what we want to achieve path to the design folder:
-------------------------------------------------------------------------------------------------------
    `./asset/design`
-------------------------------------------------------------------------------------------------------

#Team Lead
    name: Samuel Fatodu
    telegram username: @SamCares4real
    phone number: 08186988028
    sidehustle id: SH-IT-0047775

#Assistant Team Lead
    name: Ariyibi Baseet
    telegram username: ariyibi_baseet
    phone number: 08168818211
    sidehustle id: SH-IT-0093716


--------------------------------------------------------------------------------------------------------
#Projected Paths (6)
Design Folder
Asset Folder --> Img Folder and Css Folder
index (index.html, landing page)
ReadMe.txt

#Folders (4)
Design Folder
Asset Folder
Img Folder
Css Folder

---------------------------------------------------------------------------------------------------------
## MY CONTRIBUTION ##
----------------------
Pay attention to this section. Here we have names and task assignation to each participant 
 

#Git Setup
-> Before you do anything, You have to create a new branch.
-> Create a pull request with a well commited task


Name : Samuel Fatodu  - Administrative task
--------------------------------------------------------------
Task :
--->  Create Group repository and monitor every pull request
--->  Create Asset Folder as the parent folder and create img, design, font and css folder in it 


Name : Ariyibi Baseet  - Administrative task
--------------------------------------------------------------
Task :
--->  Create Documentation and sharing of task
--->  add the order summary capstone images in design folder
--->  add a comment to all html and css files
--->  restructure css file and add commenting


Name: Abiamowei Victor
--------------------------------------------------------------
Task:
---> Create index.html file (with basic html tags) in the same root directory as asset folder
---> Create style.css file inside css folder


Name: Abdulhakeem Abdurahmon
--------------------------------------------------------------
Task:
--->  add favicon.png and all required svg images for the project
--->  link the favicon.png in the head tag and display in in the broswer title bar (as logo)


Name: Adebayo Ibrahim Opeyemi
-------------------------------------------------------------
Task:
--->  create a div with a class of `order-summary-card` inside the body tag
--->  create an img tag with the src of `./asset/img/illustration-hero.svg` and a class of `img-hero-top`


Name: Abdullahi Adebayo Abdullahi
-------------------------------------------------------------
Task:
--->   create a div with a class of `content-down`
--->   create a span with a class of `summary-text` inside content-down div tag
--->   add a content `Order Summary` inside a summary-text span tag



Name: Adedeji Inioluwa
-------------------------------------------------------------
Task: 
--->  create a p tag with a class of `summary`
--->  add a content `You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like` inside summary p tag
--->  after the p tag, create a div with a class of `plan-container`


Name: Ariyibi Baseet - normal task
-------------------------------------------------------------
Task:
--->  create an img tag with a src of `./asset/img/icon-music.svg` 
--->  after the img tag create a div with a class of `plan`
--->  style the body in the css folder, add css reset,add background-image, color and display it as flex


Name: Anuoluwapo Tenibiaje
-------------------------------------------------------------
Task:
--->  create a span with a class of `annual-text` and after that create a break tag
--->  add a content `Annual Plan` to the annual-text span tag
--->  create another span tag with a content `$59.99/year` after the break tag


Name: Damilola Idris
-------------------------------------------------------------
Task:
---> create an achor tag with href of `#` and a content `Change` in it
---> change the background on smaller device (375px) using media queries in the css file
`
@media screen and (max-width:375px){
    body{
        background-image: url(./images/pattern-background-mobile.svg);
        background: hsl(225, 100%, 94%);
        width:100%;
    }
}
`


Name: Dahud Yusuf Ishola
-------------------------------------------------------------
Task:
---> create a button tag with a class of `proceed-btn` and content `Proceed to payment` after plan div tag
---> create a span with a class of `cancel-order` and a content `Cancel Order` immediately after the proceed-btn button tag


Name: Durowade Adeyemi Nathaniel
-------------------------------------------------------------
Task:
---> link the locally downloaded font (from font folder) with @font-face rule in the css file
---> add a styling to `order-summary-card` in the css file
`
.order-summary-card{
    max-width:350px;
    border-radius:15px;
    background:#fff;
    box-sizing:border-box;
    box-shadow:2px 3px 8px hsl(224, 23%, 55%);
    box-sizing:border-box;
}
`


Name: Gomina Maryam
-------------------------------------------------------------
Task:
---> add a styling to `img-hero-top` in the css file
`
.img-hero-top{
    width:100%;
    border-radius:15px 15px 0 0;
}
`


Name: Kehinde Akinola
-------------------------------------------------------------
Task:
---> add a styling to  `content-down` in the css file
`
.content-down{
    padding:20px;
    box-sizing:border-box;
}
`


Name: NNanna Echi
-------------------------------------------------------------
Task:
---> add a styling to `summary-text`. you can call `.summary-text` or using decendant selector like this in the css file:
`
.content-down .summary-text{
    text-align:center;
    font-size:25px;
    display:block;
    font-weight:900;
}
`


Name: Olowogbami Israel Akinyemi
-------------------------------------------------------------
Task:
---> add a styling to `summary` in the css file
`
.summary{
    text-align:center;
}
`


Name: Odiete Oghenemaro Great
-------------------------------------------------------------
Task:
---> add a styling to `plan-container` in the css file
`
.plan-container{
    display:flex;
    align-items:center;
    justify-content:space-between;
    background-color:hsl(225, 100%, 98%);
    padding:10px 20px;
    box-sizing:border-box;
    border-radius:10px;
}
`


Name: Renson Gitonga
-------------------------------------------------------------
Task:
---> add a styling to `plan` in the css file (use general sibling selector `>`)
`
.plan-container > .plan{
    margin-left:-10px;
}
`


Name: Simon GitTimothy Awogbuyi
-------------------------------------------------------------
Task:
---> add a styling to `annual-text` in the css file (with general sibling slector `>`)
`
.plan > .annual-text{
    text-align: center;
    font-weight:bolder;
}
`


Name: Samuel FatoduOsazuwa Osakpolor
-------------------------------------------------------------
Task:
---> add a styling to `proceed-btn` and `cancel-order` (using group selector) in the css file
`
.proceed-btn,.cancel-order{
    font-weight:bolder;
}
`
---> add a styling to `proceed-btn` in the css file
`
.proceed-btn{
    margin-top:20px;
    display:block;
    width:100%;
    font-size:16px;
    border-radius:10px;
    border:hidden;
    padding:10px 15px;
    color:#fff;
    cursor:pointer;
    background-color:hsl(245, 75%, 52%);
    box-shadow:2px 4px 8px hsl(224, 23%, 55%);
}
`


Name: Yusuf Isioye
-------------------------------------------------------------
Task:
---> add a styling(hover on proceed button) to `proceed-btn` in the css file
`
.proceed-btn:hover{
    background-color:hsl(224, 23%, 55%);
    transition:300ms ease-in-out;
}
`
---> add a styling to `cancel-order` in the css file
`
.cancel-order{
    margin-top:10px;
    display:block;
    text-align:center;
    cursor:pointer;
}
`