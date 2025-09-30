# Ex04 Places Around Me
# Date:30.09.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html:
<!Doctype html>
 <html>
    <body>
<img src="Screenshot 2025-09-30 200000.png" usemap="#image-map">
<map name="image-map">
    <area shape="rect" target="_self" alt="My home" title="My home" href="home.html" coords="937,458,1064,575" >
    <area target="_self" alt="AGS cinemas" title="AGS cinemas" href="AGScinemas.html" coords="600,890,405" shape="circle">
    <area target="_self" alt="Arulmigu vadapalani murugan temple" title="Arulmigu vadapalani murugan temple" href="Arulmigu vadapalani murugan.html" coords="800,500,350" shape="circle">
    <area target="_self" alt="Semozhipoonga" title="Semozhipoonga" href="semozhipoonga.html" coords="900,500,330" shape="circle">
    <area target="_self" alt="koyambedu" title="koyambedu" href="koyambedu.html" coords="874,636,350" shape="circle">

</map>
</body>
</html>

AGScinemas.html:

<html>
<head><title>AGS cinemas</title></head>
<body bgcolor="LightBlue">
<h1 align="center"><font color="DarkBlue"><b>CHENNAI</b></font></h1>
<h3 align="center"><font color="DarkBlue"><b>AGS cinemas</b></font></h3>
<hr size="3" color="White">
<p align="center"><font face="Georgia" size="3">
    Since its inception, AGS has swiftly and surely become a household name with regards to film production, distribution and exhibition. AGS Entertainment Pvt. Ltd. produced a host of commercially and critically successful movies like Thiruttu Payale, Yudham Sei, Avan Ivan, Madrasapattinam, Santhosh Subramanium, Maatran, Anegan, Kavan, Thani Oruvan etc. Santhosh Subramanium was recognized by the Tamil Nadu State Government as the Best Tamizh Feature Film in 2008. AGS Entertainment has also successfully distributed films like Myna, I and Kabali.
</font></p>
</body>
</html>

Arulmigu vadapalani murugan.html:

<html>

<head><title>Arulmigu vadapalani murugan</title></head>

<body bgcolor="Lightgrey">
<h2 align="center"><font color="DarkBlue"><b>Arulmigu vadapalani murugan temple</b></font></h2>

<hr size="3" color="White">

<p align="center"><font face="Georgia" size="3">
  The temple’s remarkable origin dates back to the late 19th century when devotee Annaswami Nayakar, suffering from chronic stomach ailments, initially worshipped a painted portrait of Lord Murugan in a small thatched hut. After a divine vision instructing him to worship at home rather than travel to distant temples during harsh weather, he established this sacred space around 1890. Following Annaswami’s passing, his disciple Rathinasamy Chettiyar continued the tradition and installed the main idol, with temple construction completed and the Kumbabhishekam performed by 1920. The temple gained fame through the “Arul Vaakku” (divine utterances) tradition, where devotees believed the priests’ words provided solutions to life’s challenges.  
</font></p>

</body>
</html>

home.html:

<html>
<head><title>My home</title></head>
<body bgcolor="Lightgreen">

<h2 align="center"><font color="DarkBlue"><b>My home</b></font></h2>
<hr size="3" color="White">
<p align="center"><font face="Georgia" size="3">
    My house is a place of comfort, warmth, and cherished memories. Situated in a friendly neighborhood, it stands out with its charming exterior and well-maintained garden, where a variety of colorful flowers bloom throughout the seasons, adding a touch of natural beauty to the surroundings. The interior of my house is thoughtfully designed, with spacious rooms that allow for plenty of natural light to flood in, creating a bright and airy atmosphere. The living room is the central hub, furnished with comfortable seating and decorated with family photos and artwork that reflect our personal tastes and experiences. This is where we gather to relax, watch movies, and enjoy each other’s company. The kitchen, with its modern appliances and cozy dining area, is another favorite spot, where we cook meals together and share daily stories. Each bedroom is a personal haven, offering a space for rest and reflection. My house is more than just a structure; it is a sanctuary where we find peace, create lasting memories, and feel a deep sense of belonging. It is the embodiment of our family’s love and unity, making it a truly special place.
</font></p>
</body>
</html>

koyambedu.html:

<html>
<head><title>Koyambedu</title></head>
<body bgcolor="LightBlue">

<h2 align="center"><font color="DarkBlue"><b>Koyambedu</b></font></h2>
<hr size="3" color="White">
<p align="center"><font face="Georgia" size="3">
    Koyambedu is a neighbourhood in Chennai, India. Situated in the western part of Chennai city, the Koyambedu area has become a major hub of activity in Chennai after the inauguration of the Koyambedu market in 1996 and the Chennai Mofussil Bus Terminus (CMBT) in 2002. The area is active round the clock owing to the movement of people and goods through the day, with uninterrupted transport facilities such as long-route buses, autos, share autos, vegetable goods carriers and so forth.
</font></p>
</body>
</html>

semozhipoonga.html:

<html>
<head><title>Semozhipoonga</title></head>
<body bgcolor="Lightgreen">

<h2 align="center"><font color="DarkBlue"><b>Semozhipoonga</b></font></h2>
<hr size="3" color="White">
<p align="center"><font face="Georgia" size="3">
    Semmozhi Poonga, variously spelled as Semmoli Poonga (literally translated to "Classical Language Park"), is a botanical garden in Chennai set up jointly by the Horticulture and Agricultural Engineering department of the Government of Tamil Nadu. The garden was opened on 24 November 2010 by then chief Minister M. Karunanidhi and is the first botanical garden in the city.[1] The garden is located in the Cathedral Road–Anna Salai junction, opposite the American Consulate, on the erstwhile Drive-in Woodlands Hotel. Encompassing an area of 20 acres (320 grounds),[2] it was built at a cost of ₹ 80 million. More than 500 species of plants are being grown in the area, in addition to the 80 trees that were already in existence during the development of the park, some of them being more than 100 years old. 
</font></p>
</body>
</html>
```
# OUTPUT

<img width="1919" height="1120" alt="Screenshot 2025-09-30 224409" src="https://github.com/user-attachments/assets/79479914-70ce-4311-acb8-5df68878568b" />

<img width="1919" height="609" alt="Screenshot 2025-09-30 223650" src="https://github.com/user-attachments/assets/9a13f608-09f1-4b95-9493-c502faaef182" />

<img width="1910" height="593" alt="Screenshot 2025-09-30 223715" src="https://github.com/user-attachments/assets/173ee89d-eb8c-4ca8-8d4d-0be813e99fe8" />

<img width="1919" height="690" alt="Screenshot 2025-09-30 223739" src="https://github.com/user-attachments/assets/2597bd23-8a6c-446f-810b-c018ab1611bb" />

<img width="1917" height="597" alt="Screenshot 2025-09-30 223831" src="https://github.com/user-attachments/assets/517ce162-fd2a-4fa8-ae6b-b309bfcba680" />

<img width="1919" height="604" alt="Screenshot 2025-09-30 223905" src="https://github.com/user-attachments/assets/a2c6bb5b-55ee-4f27-b92e-b73a4beee891" />






# RESULT
The program for implementing image maps using HTML is executed successfully.
