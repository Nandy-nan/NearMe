# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
<!DOCTYPE html>
<html lang="en">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <html>
        <head>
        <title>Mycity</title>
        </head>
        <body bgcolor="white">
            <h1 align="center">
            <font color="black"><b>DELHI</b></font>
            </h1>
            <h3 align="center">
                <font color="blue"><b>Nandhana.R</b> (212223040125)</b></font>
            </h3>
            <center>
                <img src="map.png"  usemap="#MyCity" height="600" width="1400">
                <map name="MyCity">
                        <area shape="rect" coords="360,230,450,280" href="toursistplace" title="INDIA GATE">     
                        <area shape="rect" coords="800,280,900,400" href="best hotel" title="JAYPEE SIDDARTH">
                        <area shape="rect" coords="420,630,520,670" href="entertainment spot" title="ADVENTURE ISLAND">
                        <area shape="rect" coords="1200,300,920,350" href="temple" title="GOLDEN TEMPLE">
                        <area shape="rect" coords="750,280,790,360" href="thater" title="PVR DIRECTORS">
                </map>
            </center>
           
    
        </body>
    </html>

tourist place.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">DELHI</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="blue" size="5.5">INDIA GATE</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Delhi,india captial territory,is a massive metropolitan area in the countrys north.<br>
            The india gate is known as all india war memorial ,it is located near the kartavya path on eastern edge of the eastern edge of cernomial axis of new delhi<br>
            sir edwin lutyenes was the chief designer.
        </p>
    </body>
</html>
best hotel.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">DELHI</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="blue" size="5.5">jAYPEE SIDDARTH</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
              jaypee siddarth is 5 star rated luxury hotel in delehi located at 3, Rajendra Place, New Delhi, Delhi 110008.it has all types of room with luxury faciltes.
              and with food facilits.
        </p>
    </body>
</html>

enterntaiment spot.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">delhi</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="blue" size="5.5">ADVENTURE ISLAND</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Spreading over 62 acres of land, Adventure Island is divided into two sections: the Amusement Park and the Lagoon or artificial lake, which are joined by a bridge. 
            While the amusement park invites thrill-seekers, the Lagoon offers a unique boating experience.
  
    
        </p>
    </body>
</html>
temple.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">delhi</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="blue" size="5.5">GOLDEN TEMPLE</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Golden Temple is spiritually the most significant shrine in Sikhism. 
            It became a centre of the Singh Sabha Movement between 1883 and the 1920s, and the Punjabi Suba movement between 1947 and 1966.
            
        </p>
    </body>
</html>
theater.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">delhi</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="blue" size="5.5">PVR DIRECTORS</font>
    </h3>
    <body bgcolor="grey" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            PVR Directors cut is a luxury movie viewing experience at ambience mall Vasant Kunj. The tickets are priced more then double. 
            They have extensive food menu inside the movie hall from sushi's rolls pizza kulchas and many more.
            
        </p>
    </body>
</html>
```
    


## OUTPUT

![Screenshot 2024-04-21 222031](https://github.com/Nandy-nan/NearMe/assets/153698914/9d42becc-094b-41d9-9271-c309f6b50f28)
![Screenshot 2024-04-21 222745](https://github.com/Nandy-nan/NearMe/assets/153698914/09a42aea-6700-4aa7-a48a-f19d900ab086)
![Screenshot 2024-04-21 223330](https://github.com/Nandy-nan/NearMe/assets/153698914/0b18d9d2-683d-4717-a739-e96ad53e024e)
![Screenshot 2024-04-21 223842](https://github.com/Nandy-nan/NearMe/assets/153698914/70db893b-b8ef-4262-813b-beea4ee40a8f)
![Screenshot 2024-04-21 224033](https://github.com/Nandy-nan/NearMe/assets/153698914/e0b216db-7212-428f-95df-462109eb0362)










## RESULT
The program for implementing image maps using HTML is executed successfully.
