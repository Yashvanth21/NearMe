# Ex03 Places Around Me
## Date: 23.02.2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html

<html>
<head>
    <title>My City</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>TIRUPATI</b></font>
    </h1>

    <h3 align="center">
        <font color="blue"><b>Ramesh Jaisurya</b></font>
    </h3>

    <center>
        <img src="MAP.png" usemap="#image-map" >

<map name="image-map">
    <area target="" alt="Tirupati Exhibition Center" title="Tirupati Exhibition Center" href="tec.html" coords="1247,485,1534,205" shape="rect">
    <area target="" alt="Faceone Pest Control Services" title="Faceone Pest Control Services" href="face.html" coords="471,203,130" shape="circle">
    <area target="" alt="Tirupati Busstand" title="Tirupati Busstand" href="bustand.html" coords="659,486,1050,505,989,622,883,663,753,621,674,550" shape="poly">
    <area target="" alt="Vishnu Nivasam" title="Vishnu Nivasam" href="visniv.html" coords="382,593,135" shape="circle">
    <area target="" alt="Jalpaan Veg Restaurant" title="Jalpaan Veg Restaurant" href="jalpan.html" coords="1296,583,1027,673" shape="rect">
</map>
        
    </center>
</body>
</html>

jalpan.html

<html>
    <head>
        <title>TEC</title>
    </head>
    <body bgcolor="cyan">
       <h1 align="center">
        <font color="red"><b>TIRUPATI</b></font>
    </h1>
        <h2>Jalpaan Veg Restaurant:</h2>
        <h3>Jalpaan Veg Restaurant, located on the ground floor of Hotel Udayee International in Tirupati, offers a modern and spacious setting for enjoying North Indian and international cuisine along with mocktails and ice cream. While it is praised for its delicious vegetarian food, it's worth noting that the restaurant is more expensive compared to other options in the area. The restaurant provides a wide range of dishes from starters to desserts, making it suitable for individuals or families looking to savor every bite</h3>
    </body>
</html>

bustand.html

<html>
    <head>
        <title>bus stand</title>
    </head>
    <body bgcolor=" grey">
       <h1 align="center">
        <font color="red"><b>TIRUPATI</b></font>
    </h1>
        <h2>Tirupati Busstand:</h2>
        <h3>The Tirupati Bus Stand is a central hub for travelers visiting the city, especially for the Tirumala Venkateswara Temple. It is known for its cleanliness and spaciousness, making it a preferred choice for pilgrims. The bus station offers direct buses to various destinations within the city and nearby towns, ensuring convenient travel for visitors.</h3>
    </body>
</html>

face.html

<html>
    <head>
        <title>Faceone</title>
    </head>
    <body bgcolor="white
    ">
       <h1 align="center">
        <font color="red"><b>TIRUPATI</b></font>
    </h1>
        <h2>Faceone Pest Control Services:</h2>
        <h3>They includes planning and implementing actions to prevent and manage pest infestations effectively. It involves understanding pest life cycles and using various methods to control pests</h3>
    </body>
</html>

tec.html

<html>
    <head>
        <title>TEC</title>
    </head>
    <body bgcolor="cyan">
       <h1 align="center">
        <font color="red"><b>TIRUPATI</b></font>
    </h1>
        <h2>Tirupati Exhibition Center:</h2>
        <h3>The Tirupati exhibition center features a new theme, exciting rides, and delicious food stalls every year</h3>
    </body>
</html>

visniv.html

<html>
    <head>
        <title>Vishnu Nivasam</title>
    </head>
    <body bgcolor="yellow">
       <h1 align="center">
        <font color="red"><b>TIRUPATI</b></font>
    </h1>
        <h2>vishnu nivasam:</h2>
        <h3>Vishnu Nivasam is a popular accommodation option for pilgrims visiting Tirupati, offering clean, affordable rooms and convenient access to the Tirumala Temple.</h3>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (83).png>) ![alt text](<Screenshot (82).png>) ![alt text](<Screenshot (81).png>) ![alt text](<Screenshot (80).png>) ![alt text](<Screenshot (79).png>) ![alt text](<Screenshot (78).png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
