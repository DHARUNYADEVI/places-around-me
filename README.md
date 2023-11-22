# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Create a django admin interface.

### Step 2:
Download your city map from google.

### Step 3:
Using ```<map>``` tag name the map.

### Step 4:
Create clickable regions in the image using ```<area>```tag.

### Step5:
Write the HTML programs for all the regions identified.

### Step 6:
Execute the programs and publish them.

## Code:
```
map.html
<!DOCTYPE html>
<html>
    <head>
        <title>
            imagemaps demo
        </title>
    </head>
    <body>
        <h1>imagemaps demo</h1>
        <img src="Dharunyadevi-hometown.jpg" usemap="#image_map">
<map name="image_map">
  <area alt="mohanurbusstand" title="mohanurbusstand" href="mohanurbusstand.html" coords="948,369,1211,444" shape="rect">
  <area alt="kaveririverbridge" title="kaveririverbridge" href="kaveririverbridge.html" coords="649,697,197" shape="circle">
  <area alt="zohospokeoffice" title="zohospokeoffice" href="zohospokeoffice.html" coords="1405,469 1402,1036 1750,774 " shape="polygon">
  <area alt="nehrunagar" title="nehrunagar" href="nehrunagar.html" coords="1296,410,1437,471" shape="rect">
  <area alt="kandhamalaikandhankoil" title="kandhamalaikandhankoil" href="kandhamalaikandhankoil.html" coords="1356,204,159" shape="circle">
</map>
 </body>
</html>
kandhamalaikandhankoil.html
<!DOCTYPE html>
<html>
    <head>
        <title>
              kandhamalaikandhankoil
        </title>
    </head>
    <body>
        <h1>kandhamalaikandhankoil</h1>
    </body>
</html>

kaveririverbridge.html
<!DOCTYPE html>
<html>
    <head>
        <title>
            kaveririverbridge
        </title>
    </head>
    <body>
        <h1>kaveririverbridge</h1>
    </body>
</html>

mohanurbusstand.html
<!DOCTYPE html>
<html>
    <head>
        <title>
            mohanurbusstand
        </title>
    </head>
    <body>
        <h1>mohanurbusstand</h1>
    </body>
</html>

nehrunagar.html
<!DOCTYPE html>
<html>
    <head>
        <title>
              nehrunagar
        </title>
    </head>
    <body>
        <h1>nehrunagar</h1>
    </body>
</html>

zohospokeoffice.html
<!DOCTYPE html>
<html>
    <head>
        <title>
              zohospokeoffice
        </title>
    </head>
    <body>
        <h1>zohospokeoffice</h1>
    </body>
</html>
```
## Output:
![Dharunyadevi-hometown](https://github.com/DHARUNYADEVI/places-around-me/assets/147473847/dd7ad2b9-a887-433f-aedb-a34c5195e289)


## Result:
The program for implementing image maps using HTML is executed successfully.
