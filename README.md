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
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Porur Map</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            overflow-y: hidden;
        }

        h1 {
            font-size: 50px;
            color: black;
            display: flex;
            justify-content: center;
            font-family: 'poppins' , sans-serif;
        }

        h2 {

            color: black;
            font-size: 30px;
            letter-spacing: 3px;
            text-align: center;
            margin-bottom: 5px;
        }

        hr {
            border: 2px solid black;
        }
    </style>
</head>
<body>

    <h1>
        Jerushlin Jose
    </h1>

    <h2>OUTLINE OF PORUR</h2>

    <hr>

    <img src="Map.png" alt="" style="height: 85vh; width: 100%;">
    <map name="Porur">
        <area target="_blank" alt="Dessi Cuppa Porur" title="Dessi Cuppa" href="dessicCuppa.html" coords="1022,471,21" shape="circle">
        <area target="_blank" alt="KATTUPAKKAM" title="KATTUPAKKAM" href="kattupakkam.html" coords="383,294,22" shape="circle">
        <area target="_blank" alt="SHREE NAGAR" title="SHREE NAGAR" href="shreenagar.html" coords="556,545,625,594" shape="circle">
        <area target="_blank" alt="Bakes and cake" title="Bakes and cake" href="Bakesandcake.html" coords="1113,289,1158,334" shape="circle">
        <area target="_blank" alt="Porur toll plaza" title="Porur toll plaza" href="porurtollplaza.html" coords="1068,237,1118,275" shape="circle">
    </map>
</body>
</html>


```


## OUTPUT

![image](https://github.com/Jerushli/NearMe/assets/120041243/0a0c00ef-df4c-4e9a-b1c1-19813d5c6e76)
![image](https://github.com/Jerushli/NearMe/assets/120041243/58b92042-af1b-4330-bb54-cf93bc6a407c)
![image](https://github.com/Jerushli/NearMe/assets/120041243/d05f2f27-f917-4a2f-bf0b-377ea8e8f5e0)
![image](https://github.com/Jerushli/NearMe/assets/120041243/7c981e3a-4ffa-4326-a9cb-4cf8fd9c4dc4)
![image](https://github.com/Jerushli/NearMe/assets/120041243/f6fa56ff-9719-4bac-b1c1-c53585c3bdfc)
![image](https://github.com/Jerushli/NearMe/assets/120041243/d4de9933-7fc2-4c1b-950a-0e5a728eb786)

## RESULT
The program for implementing image maps using HTML is executed successfully.
