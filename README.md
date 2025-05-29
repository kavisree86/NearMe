# Ex04 Places Around Me
## Date:
24/10/23
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
<title>My City</title>
</head>
<body bgcolor="gray">
<center><table border="1px">
    <tr><th><font face="Tahoma" size="10" border="10px">PORUR</font></th></tr>
    <tr><th><font face="Tahoma" size="5" >KAVISREE (720822103083)</font></th></tr>
</table></center>
    
<center>
<img src="map1.png" usemap="#MyCity" height="590" width="1490">

<map name="MyCity">
    <area target="_blank" alt="porurlake" title="porurlake" href="lake.html" coords="500,300,650,400" shape="rect">
    <area target="_blank" alt="porurjunction" title="porurjunction" href="jun.html" coords="700,500,600,300" shape="rect">
    <area target="_blank" alt="Commerzone" title="Commerzone" href="com.html" coords="900,800,600,300" shape="rect">
    <area target="_blank" alt="Bakery" title="Bakery" href="bak.html" coords="500,200,600,300" shape="rect">
    <area target="_blank" alt="GR" title="Gr" href="gr.html" coords="800,200,600,300" shape="rect">
</map>
</center>
</body>
</html>

        
    </body>
</html>
```


## OUTPUT

<img width="959" alt="Screenshot 2023-11-14 205436" src="https://github.com/kavisree86/NearMe/assets/145759687/960b3e78-b272-4f8b-ad95-b27b4be46f37">


<img width="909" alt="Screenshot 2023-11-14 210751" src="https://github.com/kavisree86/NearMe/assets/145759687/35266c16-cacf-43c6-bccf-52f0aded4dd4">
<img width="960" alt="Screenshot 2023-11-14 210910" src="https://github.com/kavisree86/NearMe/assets/145759687/3c404c83-0782-45a5-9bc5-2ddafe1d7441">

## HTML VALIDATOR


## RESULT
The program for implementing image maps using HTML is executed successfully.
