# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
### Step 1: 
Create a Django project abd app.

### Step 2:
create the html and css files based on your place in the image.
### Step 3:
Define new function in views file.

### Step 4:
Import views files and define the paths in urls file.

### Step 5:
Run the server

# Code:
## maps
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>My City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sabari Akash (22009103)</b></font>
</h3>
<center>
<img src="C:\Users\SEC\OneDrive\Pictures\Screenshots\Screenshot_20230113_020948.png" usemap="#MyCity" height="500" width="1400">
<map name="MyCity">
<area shape="rectangle" coords="230,30,260,60" href="C:\Users\SEC\Desktop\4th\busstand.html" title="Bus Stand">
<area shape="circle" coords="400,350,50" href="C:\Users\SEC\Desktop\4th\RailwayStation.html" title="Park Town Railway Station">
<area shape="circle" coords="490,500,75" href="C:\Users\SEC\Desktop\4th\muneeswartemple.html" title="Bodygaurd Muneeshwar Temple">
<area shape="rectangle" coords="490,150,870,320" href=""C:\Users\SEC\Desktop\4th\ChennaiCentral.html"" title="Chennai Central">
</map>
</center>
</body>
</html>

## bus.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="red"><b>My City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
The present Bus stand was constructed during 1985, which is in adequate. Now the Government Transport Corporation is operating a huge number of buses from various towns for providing good and sufficient conveyance facilities the public visiting this pilgrimage and tourism town. As such be the case a new bus stand would be constructed with more bays and facilities.
</b>
</font>
</p>
</body>
</html>

## railway station
<!DOCTYPE html>
<html lang="en">
<head>
<title>Railway Station</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="black"><b>Park Town Railway Station</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
A station directly opposite to the Madras Central station. It mainly caters to suburban train travel and a convenient source station to reach Egmore railway station, just one stop away on the suburban line.
It just has the basic amenities, platform seating for passengers, computerized ticketing and not much more as it caters only to suburban trains. Some refreshments like tea, dosa etc are available.
The station could be kept a bit more clean, but one doesn't have to wait long as trains follow one another in quick succession.
</b>
</font>
</p>
</body>
</html>

## chennai Central
<!DOCTYPE html>
<html lang="en">
<head>
<title>Puratchithalaivar DR. MG Ramachandran Central Railway Station</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Puratchithalaivar DR. MG Ramachandran Central Railway Station</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
<b>
Puratchi Thalaivar Dr. M.G. Ramachandran Central Railway Station, commonly known as Chennai Central (station code: MAS), is the main railway terminus in the city of Chennai, Tamil Nadu, India. It is the busiest railway station in South India and one of the most important hubs in the country. It is connected to Moore Market Complex railway station, Puratchi Thalaivar Dr. M.G. Ramachandran Central metro station, Chennai Park railway station, Chennai Park Town railway station and is 2 km from Chennai Egmore railway station. The terminus connects the city to northern India, including Kolkata, Mumbai, New Delhi as well as to Bengaluru, Ahmedabad, Guwahati, Chandigarh, Kerala, Hyderabad and different parts of India.

The century-old building of the railway station, designed by architect George Harding, is one of the most prominent landmarks of Chennai.[4] The station is also a main hub for the Chennai Suburban Railway system. It lies adjacent to the current headquarters of the Southern Railway and the Ripon Building. During the British Raj, the station served as the gateway to South India, and the station is still used as a landmark for the city and the state.

The station was renamed twice; first to reflect the name change of the city from Madras to Chennai in 1996 it was renamed from Madras Central to Chennai Central, and then to honour the AIADMK founder and the former Chief Minister of Tamil Nadu M. G. Ramachandran, it was renamed as Puratchi Thalaivar Dr. M.G. Ramachandran Central Railway Station on 5 April 2019.[5]

About 550,000 passengers use the terminus every day, making it the busiest railway station in South India.[6] Along with Chennai Egmore and Coimbatore Junction, the Central terminus is among the most profitable stations of Southern Railways.[7] As per a report published in 2007 by the Indian Railways, Chennai Central and Secunderabad were awarded 183 points out of a maximum of 300 for cleanliness, the highest in the country.[8]</b>
</font>
</p>
</body>
</html>

## temple
<!DOCTYPE html>
<html lang="en">
<head>
<title>temple</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="red"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Bodygaurd Muneeshwar Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
<b>
In 1919 CE, labourers from North Arcot district brought the idol of Lord Muneeswarar to Madras city (present Chennai).[3] They placed it under a neem tree adjoining the military barracks of the Britishers. One of the British Commanders showed his objection. The same day he met with an accident. He started believing that the idol has some powers so he let it be there. From the day many devotees around Chennai worship this Lord and constructed a temple around the idol. They believe that the main deity of the temple Lord Muneeswarar will save them from accidents. So the deity got the name of Bodyguard Muneeswarar. This temple is now visited by thousands of devotees each day.[4]</b>
</font>
</p>
</body>
</html>


# Output:
![Screenshot_20230113_083114](https://user-images.githubusercontent.com/119390227/212353386-89aaca4a-dec2-4bd5-a00a-0afa4b4983b6.png)

# Result:

