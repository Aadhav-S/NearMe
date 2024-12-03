# Ex04 Places Around Me
## Date: 19/11/24

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
map.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body>
        <h1 align="center">
            <font color="black"><b>CUMBUM</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>AADHAV S(24005747
                
                )</b></font>
  
                
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Kambarayar perumal temple" title="Kambarayar perumal temple" href="temple.html" coords="955,332,1159,393" shape="rect">
    <area target="" alt="Pennycuick garden" title="Pennycuick garden" href="garden.html" coords="945,848,1137,911" shape="rect">
    <area target="" alt="My School" title="My School" href="school.html" coords="1098,420,1266,508" shape="rect">
    <area target="" alt="Thambis theatre" title="Thambis theatre" href="theatre.html" coords="1028,88,1215,164" shape="rect">
    <area target="" alt="My home town" title="My home town" href="map.html" coords="0,9,1911,1007" shape="rect">
</map>
</center>
    </body>
</html>
temple.html
<html>
    <head>
        <title>KAMBARAYAR PERUMAL TEMPLE</title>
    </head>
    <body bgcolor="lightyellow">
        <h1 align="center">
            <font color="red"><b>CUMBUM</b></font> 
        </h1>
        <h3 align="center">
            <font color="Brown"><b>KAMBARAYA PERUMAL TEMPLE</b></font>

        </h3>
        <hr size="4" color="black">
        <p align="justify">
            <font face="georgia" size="5">
                This temple was built by viswanatha nayak who ruled madurai. Lord Vishnu appeared in his dream and told
                that there is a idol below the stone post in the foothills of western ghats and it was him.He told him to 
                take the idol and built a temple and worship him.So the king raised a temple and named it as Kambarayar perumal
                as it was found under the stone post(KAMBAM) and hence the name of our place as "cumbum".He also bring kaasi 
                vishwanathar idol from kasi-varanasi and raised a temple for him also.
            </font>
        </p>

    </body>
</html>
school.html
<html>
    <head>
        <title>MY SCHOOL</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
            <font color="red"><b>CUMBUM</b></font>
        </h1>
        <h3 align="center">
            <font color="lime"><b>Nagamani Ammal Memorial Matriculation Higher Secondary School</b></font>
        </h3>
        <hr size="4" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Our school has Private building. It has got 36 classrooms for instructional purposes. 
                All the classrooms are in good condition. It has 2 other rooms for non-teaching activities.
                The school has a separate room for Head master/Teacher. The school has Pucca boundary wall.
                The school has have electric connection. The source of Drinking Water in the school is 
                Tap Water and it is functional. The school has 35 boys toilet and it is functional. and 
                15 girls toilet and it is functional. The school has a playground. The school has a library 
                and has 3500 books in its library. The school does not need ramp for disabled children to 
                access classrooms. The school has 20 computers for teaching and learning purposes and all 
                are functional.
            </font>
        </p>
    </body>
</html>
garden.html
<html>
    <head>
        <title>PENNYCUICK GARDEN</title>
    </head>
    <body bgcolor="lime">
        <h1 align ="center">
            <font color="dark pink"><b>CUMBUM</b></font>
        </h1>
        <h3 align="center">
            <font color="red"><b>PENNYCUICK GARDEN</b></font>
        </h3>
        <hr size="4" color="dark pink">
        <p align="justify">
            <font face="red" size="5">
                A garden is a peaceful retreat where nature and creativity come together in harmony. It offers
                a space for plants to thrive, from vibrant flowers to lush greenery, each adding its own charm
                and beauty. Gardens are not only visually soothing but also provide a sensory experience, with 
                the scent of blooming flowers, the sound of rustling leaves, and the feeling of soft grass underfoot.
                 Whether large or small, a garden encourages relaxation, exploration, and connection to the environment.
                  It also fosters a sense of accomplishment as one nurtures and watches plants grow, creating a sanctuary
                   of calm and tranquility.
            </font>
        </p>

    </body>
</html>
theatre.html
<html>
    <head>
        <title>THAMBIS THEATRE</title>
    </head>
    <body bgcolor="lightcoral">
        <h1 align="center">
            <font color="black"><b>CUMBUM</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>THAMBIS THEATRE</b></font>
        </h3>
        <hr size="4" color="black">
        <p align="justify">
            <font face="Georgia" size="5">
                Thambis theatre was a well known theatre in our locality.We love this theatre a lot as we had a lot
                of memories in this theatre. I used to watch all thalapathy movies in this theatre.Before 1 year this
                theatre was closed due to renovation work. After renovating,it gave a huge comeback with high sound quality,
                comfy sofas and yummy snacks,etc...This theatre use dolby atmos which has good sound quality.
                This theatre is one of the favourite of mine and I'm missing it now.
            </font>
        </p>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (26).png>)
## RESULT
The program for implementing image maps using HTML is executed successfull