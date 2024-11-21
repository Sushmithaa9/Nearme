# Ex04 Places Around Me
## Date: 21.11.24

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

<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>My Home Town</title>
   <style>
       img{
           padding-top: 1%;
       }
       h1{
           text-align: center;
           font-size: 48px;
           color: white;
       }
       body{
           background-color:BLACK;
       }
   </style>
</head>
<body>
   <h1>My Home Town</h1>
   <center><img src="Map.png" usemap="#image-map" width="1400px" height="800px">
   <map name="image-map">
    <area target="" alt="VR CHENNAI" title="VR CHENNAI" href="t1.html" coords="80,501,341,577"" shape="rect">
    <area target="" alt="ROHINI SILVER SCREENS" title="ROHINI SILVER SCREEENS" href="t2.html" coords="14,697,275,773" shape="rect">
    <area target="" alt=" THE LIVING ROOM" title="THE LIVING ROOM" href="t3.html" coords="660,263,939,335" shape="rect">
    <area target="" alt="TASTE OF ITALY" title="TASTE OF ITALY" href="t4.html" coords="916,621,1195,693" shape="rect">
    <area target="" alt="ANNA TOWER" title="ANNA TOWER" href="p.html" coords="247,438,526,510" shape="rect">

</map>
</body>
</html>
p1.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VR MALL</title>
    <style>
        h1 {
            color:rgb(48, 181, 181);
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(139, 139, 208);
        }

        body {
            background-color: rgb(231, 231, 163);
        }
    </style>
</head>

<body>
    <h1>VR MALL</h1>
    <hr color="black">
    <p><b>
            A VR mall is a digital, immersive shopping environment that allows users to explore virtual storefronts and
            purchase products in a 3D, interactive space. Using a virtual reality headset, shoppers can navigate through
            a virtual mall, walk into digital stores, and interact with products in ways that simulate real-life
            shopping. Some VR malls offer unique features like trying on clothes virtually, inspecting gadgets in 3D, or
            even attending virtual events, providing an engaging and futuristic shopping experience that goes beyond
            traditional online shopping.
            <br><br>
            In a VR mall, retailers create digital versions of their physical stores, making it possible for customers
            to experience their products in a more interactive way than on a website. These virtual stores can showcase
            items in 3D, and users can get a better sense of size, texture, and design. The VR mall can also integrate
            social features, allowing friends to shop together or chat with other customers. While still in its early
            stages, this type of shopping offers convenience, novelty, and a glimpse into the future of retail, where
            shopping merges with immersive digital worlds.




        </b></p>
    <br><br>
    <hr color="black">
</body>

</html>

p2.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="TASTE OF ITALY" content="width=device-width, initial-scale=1.0">
    <title>living room</title>
    <style>
        h1 {
            color: rgb(213, 209, 237);
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(24, 96, 88);
        }

        body {
            background-color: rgb(175, 149, 131);
        }
    </style>
</head>

<body>
    <h1>TASTE OF ITALY</h1>
    <hr color="black">
    <p><b>
            **Taste of Italy** is a popular restaurant or culinary experience that brings authentic Italian flavors to
            its customers. Whether it's a restaurant, food festival, or catering service, "Taste of Italy" emphasizes
            the use of high-quality, fresh ingredients and traditional Italian cooking techniques to create a diverse
            range of dishes. From classic pasta and pizza to regional specialties like risotto, bruschetta, and
            tiramisu, the offerings are often crafted to reflect the rich culinary heritage of Italy. The focus is on
            delivering bold, simple, and flavorful meals, often using locally-sourced produce, cheeses, meats, and olive
            oils to create an experience that is as close to dining in Italy as possible.
            <br><br>
            In addition to its food, "Taste of Italy" typically creates an atmosphere that mirrors the charm and warmth
            of Italian culture, with a welcoming ambiance and rustic decor. It may offer a variety of dining options,
            from casual meals to fine dining experiences, and even extend its services to provide Italian cooking
            classes, wine pairings, or events that celebrate Italian traditions. Whether you're enjoying a meal with
            friends and family or exploring Italy’s regional cuisines, a "Taste of Italy" experience provides a genuine
            connection to Italy's rich food culture and culinary artistry.





        </b></p>
    <br><br>
    <hr color="black">
</body>

</html>

p3.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="ANNA TOWER" content="width=device-width, initial-scale=1.0">
    <title>ANNA tower</title>
    <style>
        h1 {
            color: rgb(100, 92, 146);
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(142, 219, 181);
        }

        body {
            background-color: rgb(204, 132, 150);
        }
    </style>
</head>

<body>
    <h1>ANNA TOWER</h1>
    <hr color="black">
    <p><b>
            **Anna Tower** is a well-known landmark and commercial complex located in Chennai, India. Situated in the
            heart of the city, it is often recognized for its distinctive architecture and its role as a hub for
            business and retail activities. The tower houses office spaces, shops, and other commercial establishments,
            making it a key location for professionals and businesses operating in Chennai. Over the years, Anna Tower
            has gained popularity for its strategic location and accessibility, with easy connectivity to major roads,
            public transport, and nearby commercial districts.
            <br><br>
            In addition to its business functions, Anna Tower also plays a role in the city's skyline, with its modern
            design and towering structure adding to the urban landscape. The building is often frequented by people for
            its commercial offerings, which range from offices to retail outlets and dining options. The tower is named
            after the iconic Anna Nagar area, one of Chennai's prominent neighborhoods, and is considered an important
            part of the city's growth and development in terms of both commerce and urban infrastructure.





        </b></p>
    <br><br>
    <hr color="black">
</body>

</html>

p4.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="ROHINI SILVER SCREENS" content="width=device-width, initial-scale=1.0">
    <title>Rohini Silver Screens</title>
    <style>
        h1 {
            color: rgb(224, 150, 212);
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(1, 1, 21);
        }

        body {
            background-color: rgb(217, 232, 194);
        }
    </style>
</head>

<body>
    <h1>ROHINI SILVER SCRENS</h1>
    <hr color="black">
    <p><b>
            Rohini Silver Screens is a popular chain of cinema halls located in Chennai, India, known for its rich
            history and commitment to providing a high-quality movie-watching experience. Established in the 1980s, it
            has earned a reputation for its comfortable and well-maintained theaters, catering to a diverse audience.
            The theaters are equipped with modern sound systems, high-definition screens, and air-conditioned
            facilities, ensuring a pleasant experience for moviegoers. Rohini Silver Screens often screens a variety of
            films, including Tamil, Telugu, Hindi, and other regional languages, attracting a wide range of film
            enthusiasts.
            <BR></br>
            Over the years, Rohini Silver Screens has expanded to include multiple locations, each with its unique
            features, while maintaining its commitment to customer satisfaction. The chain is well-regarded not only for
            the cinematic experience it offers but also for its strategic locations in key areas of Chennai. In addition
            to regular movie screenings, Rohini Silver Screens hosts special events, premieres, and festivals, making it
            a popular choice for film lovers looking to enjoy the latest releases in a comfortable, state-of-the-art
            environment.








        </b></p>
    <br><br>
    <hr color="black">
</body>

</html>
p5.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="THE LIVING ROOM" content="width=device-width, initial-scale=1.0">
    <title>living room</title>
    <style>
        h1 {
            color: rgb(174, 227, 187);
            text-align: center;
            font-size: 48px;
        }

        p {
            padding-top: 2%;
            font-size: 28px;
            padding-right: 5%;
            padding-left: 2%;
            color: rgb(29, 193, 168);
        }

        body {
            background-color: rgb(220, 192, 172);
        }
    </style>
</head>

<body>
    <h1>THE LIVING ROOM</h1>
    <hr color="black">
    <p><b>
            **The Living Room** is a modern and inviting space designed for relaxation, entertainment, and socializing
            within a home. Traditionally, it serves as the central gathering area, where family and friends come
            together to converse, watch TV, or enjoy activities. The living room often features comfortable seating,
            such as sofas and chairs, along with decorative elements like rugs, artwork, and lighting that create a warm
            and welcoming atmosphere. Depending on personal style, it can range from minimalist and contemporary to cozy
            and traditional, reflecting the homeowner's tastes and lifestyle.
            <br><br>
            In recent years, the living room has evolved beyond just a functional space to become a multifunctional hub.
            It’s not only a place for watching TV and hosting guests but also serves as a home office, a spot for
            gaming, or even a quiet reading nook. With advancements in technology, modern living rooms are often
            equipped with smart home devices, home theaters, and integrated sound systems, creating a more immersive
            entertainment environment. Whether for relaxation or entertainment, the living room remains one of the most
            important and versatile spaces in the home.






        </b></p>
    <br><br>
    <hr color="black">
</body>

</html>


```

## OUTPUT
![alt text](<Screenshot 2024-11-19 144615.png>)
![alt text](<Screenshot 2024-11-19 144629.png>)
![alt text](<Screenshot 2024-11-19 144639.png>)
![alt text](<Screenshot 2024-11-19 144654.png>)
![alt text](<Screenshot 2024-11-19 144703.png>)
![alt text](<Screenshot 2024-11-19 144711.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
