# Ex04 Places Around Me
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
Map.html
<!DOCTYPE html>
<html lang="en">
 <head>
 <title>my city</title>
 </head>
 <body bgcolor="cyan">
 <h1 align="center">
 <font color="red"><b>map.html</b></font>
 </h1>
 <h3 align="center">
 <font color="blue"><b>Nithiyaneranjan</b></font>
 </h3>
 <center>
 <img src="Screenshot from 2023-12-28 19-27-18.png" usemap="#image_map">
 <map name="image_map">
 <area alt="Islamiah School" title="Islamiah School" href="" 
coords="294,229,295,230" shape="rect">
 <area alt="Hospital" title="Hospital" href="" coords="648,304,649,305" 
shape="rect">
 <area alt="Chennai Hot Puffs" title="Chennai Hot Puffs" href="" 
coords="563,407,564,408" shape="rect">
 <area alt="CM Function Hall" title="CM Function Hall" href="" 
coords="21,249,21,250" shape="rect">
 <area alt="SNS Hardware paints" title="SNS Hardware paints" href="" 
coords="466,200,467,201" shape="rect">
 </map>
 </center>
 </body>
</html>
SNS hardware.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>SNS Hardware paints</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Vaniyambadi</b></font>
</h1>
<h3 align="center">
<font color="black"><b>SNS Hardware paints</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
 There are plenty of Hardware Shops in this locality. S N Hardware in Vaniyambadi HO, 
Vaniyambadi is a popular choice though. It has received a 4.0 rating by the people who have 
visited before.
</font>
</p>
</body>
</html>
CM Function Hall
<!DOCTYPE html>
<html lang="en">
<head>
<title>CM Function Hall</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="red"><b>Vaniyambadi</b></font>
</h1>
<h3 align="center">
<font color="black"><b>CM Function Hall</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
 This is one of the grand function hall in vaniyambadi. Many VIP's functions are goes in 
this function hall.So,this is one of the remarkable function hall in vaniyambadi.
</font>
</p>
</body>
</html>
Chennai Hot puffs
<!DOCTYPE html>
<html lang="en">
<head>
<title>Chennai Hot Puffs</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Vaniyambadi</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Chennai Hot Puffs</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
 One of the famous bakery in town. Known for engagement, Birthday and other events 
cakes. They have variety of cakes with appealing designs. 
</font>
</p>
</body>
</html>
Hospital.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Hospital</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Vaniyambadi</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hospital</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
 Kafeel Multispeciality Hospital in Vaniyambadi Ho, Vaniyambadi is a top player in the 
category Hospitals in the Vaniyambadi. This well-known establishment acts as a one-stop 
destination servicing customers both local and from other parts of Vaniyambadi. Over the 
course of its journey, this business has established a firm foothold in it's industry. The belief 
that customer satisfaction is as important as their products and services, have helped this 
establishment garner a vast base of customers, which continues to grow by the day. 
</font>
</p>
</body>
</html>
School.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Islamiah School</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Vaniyambadi</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Islamiah School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
 The Muslims of Vaniyambadi established the Vaniyambadi Muslim Educational Society in 
1901 with a view to translate the message of Sir Syed Ahmed Khan to provide secular 
education to the people of Arcot region in general and Muslims in particular.This is one of 
the best school in vaniyambadi.
</font>
</p>
</body>
</html>
```

## OUTPUT
![image](https://github.com/SanjayBalaji0/NearMe/assets/145533553/12577455-8ad1-4056-bd0a-9b339a52e4c7)

![image](https://github.com/SanjayBalaji0/NearMe/assets/145533553/56d89b0a-667a-4ce2-b405-26db694a3902)

![image](https://github.com/SanjayBalaji0/NearMe/assets/145533553/0616f80f-6181-4ed3-9bb7-b556df90bdf4)

![image](https://github.com/SanjayBalaji0/NearMe/assets/145533553/2c0d8441-6a81-4265-a07d-0e94fbcaa5ae)




## RESULT
The program for implementing image maps using HTML is executed successfully.
