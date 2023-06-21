# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Create a new django project and app

### Step 2:
Add a new imagemap html file in templates and neede images in static folder and define it in settings.

### Step 3:
Type ur image map code in the html with coordinates and target file to redirect on click

### Step 4:
Define your components pages and create content in such a way that it gives information about place which is being clicked

### Step 5:
Include contents for your subpages and map them using urls and views

## Code:
```python
index.html:
<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Map
        </title>
    </head>
    <body >
        <h1 align="center" >
            <font color="red" >
                    Image Map Of My Home Town
            </font>


            
        </h1>
        <h3 align="center">
        <font color="blue" face ="cursive">
            SACHIN.C (212222230125)
        </font>
            
        </h3>
        <center>
        <img id="Image-Maps-Com-image-maps-2023-04-20-073858" src="places.jpeg" border="0" width="1831" height="887" orgWidth="1831" orgHeight="887" usemap="#image-maps-2023-04-20-073858" alt="" />
<map name="image-maps-2023-04-20-073858" id="ImageMapsCom-image-maps-2023-04-20-073858">
<area  alt="" title="home" href="home.html" shape="rect" coords="1118,427,1168,477" style="outline:none;" target="_self"     />
<area  alt="" title="school" href="school.html" shape="rect" coords="1290,590,1340,640" style="outline:none;" target="_self"     />
<area  alt="" title="shop" href="shop.html" shape="rect" coords="1391,841,1432,880" style="outline:none;" target="_self"     />
<area  alt="" title="temple" href="temple.html" shape="rect" coords="1539,537,1580,576" style="outline:none;" target="_self"     />
<area  alt="" title="sports" href="sports.html" shape="rect" coords="861,480,902,519" style="outline:none;" target="_self"     />
<area shape="rect" coords="1829,885,1831,887" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
</map>



        </center>
        <p align="center">
            <font color="maroon"  face="Comic Sans MS" >
                This Image Map shows various locations around my home.<br>
                Click the location and get information about it.
            </font>
        </p>


    </body>
</html>


home.html:
<!DOCTYPE html>
<html>
<head>
    <title>
        HOME
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        MY HOME
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is my home where I live happily with my family.<br></LI>     
            <LI>My mother and Father takes care of me.<br></LI>
            <LI>I enjoy my stay at home by playing video games whenever im free.<br></LI>
            
        </OL>


    </font>
    <font color ="red" face = "cursive" size="16" > 
    "HOME IS WHERE OUR STORY BEGINS"
    </font>




</p>


</body>


</html>

temple.html:
<!DOCTYPE html>
<html>
<head>
    <title>
        TEMPLE
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        TEMPLE
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is a Temple.<br></LI>
            <LI> This is my home where I live happy with my family<br></LI>       
            <LI>This is where me and my family occasionally pray<br></LI>
           
        </OL>


    </font>
    




</p>


</body>


</html>

sports.html:
<!DOCTYPE html>
<html>
<head>
    <title>
        DECATHLON
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        SPORT CENTRE
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>Sports equipment can be bought here.<br></LI>     
            <LI>All the goods are very cheap.<br></LI>
            <LI>There are many different options for the same equipment.<br></LI>
            
        </OL>


    </font>




</p>


</body>


</html>

shop.html:
<!DOCTYPE html>
<html>
<head>
    <title>
        SHOP
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        SHOP
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is a grocery shop.<br></LI>  
            <LI>We sometimes buy our groceries from this shop.<br></LI>  
            <LI>There is a chaat shop outside the shop<br></LI>
            <LI>All my chaat cravings are fulfilled in that shop.<br></LI>
        </OL>


    </font>




</p>


</body>


</html>

school.html:

<!DOCTYPE html>
<html>
<head>
    <title>
        SCHOOL
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive">
        SCHOOL !
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is a school.<br></LI>     
            <LI>School life is undeniably one of the best memories of every college student.<br></LI>
            <LI>People usually dont realise it until its done.<br></LI>
        </OL>

    </font>





</p>


</body>


</html>

```

## Output:

##INDEX
![image](https://github.com/Sachin-vlr/places-around-me/assets/113497666/3b026df8-a646-413b-8661-785b33d974b9)

##HOME
![image](https://github.com/Sachin-vlr/places-around-me/assets/113497666/fa1aa5a1-33ca-48ea-a7a6-aaccf14b374e)

##TEMPLE
![image](https://github.com/Sachin-vlr/places-around-me/assets/113497666/567f18bd-a175-489a-8e10-fcb614894cdd)

##SCHOOL
![image](https://github.com/Sachin-vlr/places-around-me/assets/113497666/92fd7823-9669-400a-9db4-7a9f8025d20e)

##SPORTS
![image](https://github.com/Sachin-vlr/places-around-me/assets/113497666/81d76e0c-3a07-4713-9bc1-99978a7aa519)


## Result:
Thus image mapping has been accomplished

