# Ex03 Places Around Me
## Date: 10.02.2026

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
        <title> image map</title>
    </head>
    <body>
        <h1> Avadi </h1>
        <h3> logamithra.k (25005891) </h3>
        <img src="Screenshot (4).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="lake green park" title="lake green park" href="park.html" coords="920,660,742,565" shape="rect">
    <area target="" alt="Eswar residency" title="Eswar residency" href="hotel.html" coords="895,346,93" shape="circle">
    <area target="" alt="annapoorani restaurant" title="annapoorani restaurant" href="restaurant.html" coords="995,168,888,163,805,215,886,244,998,243" shape="poly">
    <area target="" alt="little hearts residency" title="little hearts residency" href="residency.html" coords="1164,309,107" shape="circle">
    <area target="" alt="selvi mahal" title="selvi mahal" href="mahal.html" coords="1761,520,1917,580" shape="rect">
    </body>
</html>

hotel.html
<html>
    <head> <title> Eswar residency </title> </head>
    <body bgcolor="green"> 
        <h1>
            Avadi
        </h1>
        <h3> Eswar residency </h3>
        <p> Hotel O Eswar Residency Avadi, Chennai (updated prices 2026) is a 3-star property located in Avadi, Chennai, offering 30 air-conditioned rooms with free Wi-Fi, TVs, and 24-hour service </p>
    </body>
    </html>

    mahal.html
    <html>
    <head> <title> selvi mahal  </title> </head>
    <body bgcolor="blue"> 
        <h1>
            Avadi
        </h1>
        <h3> selvi mahal </h3>
        <p> Selvi Mahal in Avadi, Chennai, located on Poonamallee Avadi Road (Veeragavapuram, Kaduvetti), is a well-known, fully air-conditioned kalyana mandapam suitable for weddings and events. It features a hall capacity of about 400 guests, 7 AC rooms, generator backup, and parking for 50 cars and 100 bikes.  </p>
    </body>
    </html>

    park.html
    <html>
    <head> lake green park  </head>
    <body bgcolor="grey"> 
        <h1>
            Avadi
        </h1>
        <h3> lake green park </h3>
        <p> Paruthipattu Lake Green Park (Avadi Eco Park) is a scenic, eco-friendly park on the Avadi-Poonamallee road featuring a large restored lake with, a 3-km walking track, children's play area, and pedal boatin </p>
    </body>
    </html>

    residency.html
    <html>
    <head> <title> little hearts residency  </title> </head>
    <body bgcolor="pink"> 
        <h1>
            Avadi
        </h1>
        <h3> little hearts residency </h3>
        <p> Prime Location, Easy access to industrial zones, tech parks, Defence Area and local eateries
Welcome to Little Hearts, your cozy retreat nestled in the heart of Avadi, Chennai — a destination where comfort meets convenience, and every stay feels like home.  </p>
    </body>
    </html>

    resaurant.html
    <html>
    <head> <title> annapoorani restaurant </title> </head>
    <body bgcolor="red"> 
        <h1>
            Avadi
        </h1>
        <h3> annapoorani restaurant </h3>
        <p> Annapoorani (or Annapoorna) in Avadi, Chennai, is a popular 100% vegetarian restaurant and cafe, featuring traditional South Indian, Chinese, and cafe-style dishes </p>
    </body>
    </html>

```

## OUTPUT
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (18).png>)
![alt text](<Screenshot 2026-02-10 100944.png>)
![alt text](<Screenshot 2026-02-10 100929.png>)
![alt text](<Screenshot 2026-02-10 101017.png>)
![alt text](<Screenshot 2026-02-10 101040.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
