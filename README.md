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

</head>
<script>
   function coordinate (event) {
         let x =event.clientX;
         let y =event.clientY;
document.getElementById("text1").value = x;
document.getElementById("text2").value = y;
}
</script>
<body>
<img src="map1.PNG" width="1000px" usemap="#MapNew" onmousemove="coordinate(event)"> <br>
<MAP name="MapNew">
<AREA shape="RECT" coords="61,205,244,277" href="https://apolloartsandsciencecollegechennai.ac.in/" Title="Apollo Arts and Science">
<AREA shape="RECT" coords="334,305595,401" href="https://www.saveetha.ac.in/" Title="Saveetha Engineering College">
<AREA shape="RECT" coords="672,490,848,541" href="https://dmice.ac.in/" Title="DMI college of engineering"> 
<Area shape="RECT" coords="693,430,855,485" href="https://www.loyolo.in/" title="Loyolo Institute">
</MAP>
X Co-ordinate <input type="text" name="" id="text1">
Y Co-ordinate <input type="text" name="" id="text2">
</body>
</html>     
```
## OUTPUT
![320367623-9aae878c-f06b-4ccb-8f67-8be059758a48](https://github.com/codedbykishore/NearMe/assets/147139122/6d05fd76-bac1-4769-ad4a-fd598c7e307b)







## RESULT
The program for implementing image maps using HTML is executed successfully.
