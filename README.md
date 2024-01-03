# Ex04 Places Around Me
## Date: 17-11-2023

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
<title>HOME TOWN</title>
</head>
<body>
<h1 align="center">
<font color="DeepPink"><b>KANYAKUMARI</b></font>
</h1>
<h3 align="center">
<font color="Magenta"><b>Vimala Sahana.W (23013213)</b></font>
</h3>
<center>
<img src="map.png" usemap="#HOMETOWN" height="610" width="1450">
<map name="HOMETOWN">
<area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">
<area shape="circle" coords="920,450,300" href="mandapam.html" title="Mahatma Gandhi Mandapam">
<area shape="circle" coords= "590,450,30" href="rock.html" title="VIVEKANANDA ROCK MEMORIAL">
<area shape="circle" coords= "920,150,140" href="tower.html" title="KannyaKumari View Tower">
<area shape="circle" coords= "950,920,700" href="beach.html" title="The Hidden Twin Beach">
<area shape="circle" coords= "450,320,100" href="temple.html" title="Bhagavathi Temple">


</map>
</center> 
</body>
</html>

beach.html
<html>
<head>
<title> MY NATIVE</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="SeaGreen"><b>KANYA KUMARI</b></font>
</h1>
<h2 align="center">
<font color="red"><b>The Hidden Twin Beach</b></font>
</h2>
<hr size="3" color="pink">
<p align="justify">
<font face="Ariel" size="5">
Twin Beach in the stunning metropolis of Kanyakumari. If you've got been to The Hidden Twin Beach earlier than and think that some information is missing, you could contribute to the page and make it higher for the future users. With lots of places to visit inside the Kanyakumari, ensure you seize a bite at the nearby restaurants serving scrumptious cakes, coffees or some unique delicacies of the India. And if want to treat your self to a special experience, you could also attempt some worldwide cuisines. If you are the type who plans all the way down to the remaining detail, you'll get all the required data right here.

All the important points of interest like the nearest banks and ATMs, internet cafes, pharmacies and the local traveler information centre are to be had here. When it comes to transportation, gas stations and parking spots are at your disposal. Also listed are the general public delivery options like bus stations and railway stations near The Hidden Twin Beach. You can continually book an lodging close to The Hidden Twin Beach, Kanyakumari from TripHobo. 

</body>
</html>

mandapam.html
<html>
<head>
<title> My Home Town</title>
</head>
<body bgcolor="Beige">
<h1 align="center">
<font color="OrangeRed"><b>KANYA KUMARI</b></font>
</h1>
<h2 align="center">
<font color="IndianRed"><b>Mahatma Gandhi Mandapam</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Ariel" size="5">
Located near the shores of Kanyakumari, Mahatma Gandhi Memorial was built in the honour of Mahatma Gandhi, the father of our nation. Also known as Gandhi Mandapam, it is an important part for every Kanyakumari tour, presenting a glimpse into the historical richness of India and into life of the great man that India had seen.

Mahatma Gandhi has visited Kanyakumari twice, in the year of 1925 and then in 1937. After his demise in 1948, his ashes were kept in 12 different urns so as to transfer them to different parts of the country. One of these urns was brought to Kanyakumari. Before immersions, it was kept at the spot where the memorial is built now for public so that they can pay their last homage to one of the greatest sons of India. Later the ashes were immersed in the sea waters at Kanyakumari. Later Mahatma Gandhi Memorial or Gandhi Mandapam was built at the same place.



</p>
</body>
</html>

rock.html
<html>
<head>
<title> MY NATIVE</title>
</head>
<body bgcolor="AliceBlue">
<h1 align="center">
<font color="Navy"><b>KANYA KUMARI</b></font>
</h1>
<h2 align="center">
<font color="Blue"><b>VIVEKANANDA ROCK MEMORIAL</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Ariel" size="5">
Vivekananda Rock Memorial is a monument and popular tourist attraction in Kanyakumari, India's southernmost tip.The memorial stands on one of the two rocks located about 500 meters off mainland of Vavathurai. It was built in 1970 in honour of Swami Vivekananda, who is said to have attained enlightenment on the rock. According to legends, it was on this rock that Goddess Kanyakumari (Parvathi) performed tapas in devotion of lord Shiva. A meditation hall known as Dhyana Mandapam is also attached to the memorial for visitors to meditate. The design of the mandapa incorporates different styles of temple architecture from all over India.The rocks are surrounded by the Laccadive Sea where the three oceans Bay of Bengal, the Indian Ocean and the Arabian Sea meets. The memorial consists of two main structures, the Vivekananda Mandapam and the Shripada Mandapam.
</p>
</body>
</html>

temple.html
<html>
<head>
<title> MY NATIVE</title>
</head>
<body bgcolor="Cornsilk">
<h1 align="center">
<font color="Maroon"><b>KANYA KUMARI</b></font>
</h1>
<h2 align="center">
<font color="Seinna"><b> Bhagavathi Temple</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Ariel" size="5">

Mandaikadu Bhagavathi Temple is a Hindu temple dedicated to the Hindu goddess Parvati (known as Bhagavathi). It is located near Colachel in the western coast of Kanyakumari district, Tamil Nadu. This is one among the most renowned and important Hindu temples in the district.

This temple on the sea shore is a sought after pilgrim centre for both people of Tamil Nadu and Kerala. Due to some unknown reasons people from Kollam district in Kerala frequent this temple and according to some versions this is due to the links to erstwhile Venadu, an ancient kingdom whose capital was Kollam. Venadu traces the links to imperial Cheras, from the three kingdoms of extreme south India Chera, Chola and Pandya. These are said to be three brothers from ancient Porkai, near Thiruchendoor. Travancore kings were from the Chera lineage as believed. Many temples in the region are traced to Chera and Pandya lineages, the former more.
</p>
</body>
</html>

tower.html
<html>
<head>
<title> MY NATIVE</title>
</head>
<body bgcolor="HoneyDew">
<h1 align="center">
<font color="SeaGreen"><b>KANYA KUMARI</b></font>
</h1>
<h2 align="center">
<font color="Pink"><b>KannyaKumari View Tower</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Ariel" size="5">

Undoubtedly one of the places that offer the best scenic views and sceneries of the clear blue seas and the never-ending sky that meets it at infinity, the View Tower is located in the town of Kanyakumari in Tamil Nadu in India. The View Tower and the telescope that accompanies it provides a panoramic view of not only the surrounding seashore and landscape but also of the Vivekananda Rock Memorial, Thiruvalluvar Statue and other monuments that can be seen from there. The famous Kumari Amman Temple, which is visited by devotees from all parts of the country, is also located at a walking distance and must be visited while on a trip here.

The views of the sunrise and sunset are exceptionally breathtaking when seen from the view tower, and this is perhaps precisely why visitors flock to this destination in large numbers all year round. In fact, tourists claim that from the view tower, they feel as if they can touch the sun even though it is at a distance: this is how magnificent the views are. The gentle breeze and the captivating beauty of the view tower enchant one's mind and refresh the mind and soul. The place is also the perfect spot for photographers to capture the beauties and bounties of nature. All of these factors make the View Tower a must visit site in all of Kanykamuri, and you should include it in your itinerary while here in this part of south India.
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot 2024-01-03 143316.png>)
![Alt text](<Screenshot 2024-01-03 140029.png>)
![Alt text](<Screenshot 2024-01-03 140047.png>)
![Alt text](<Screenshot 2024-01-03 143144.png>)
![Alt text](<Screenshot 2024-01-03 140016.png>)
![Alt text](<Screenshot 2024-01-03 142832.png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
