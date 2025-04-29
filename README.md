# Ex04 Places Around Me
## Date:24-04-2025

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
### Map.html
```
<html>
<head>
  <title>My City</title>
</head>
<body>
  <h1 align="center">
    <font color="red"><b>PATTABIRAM</b></font>
  </h1>
  <h3 align="center">
    <font color="blue"><b>Dhruv D (212224100013)</b></font>
  </h3>
  <center>
    <img src="map.png" usemap="#MyCity" width="1919" height="730">
    <map name="MyCity">
        <area shape="rect" coords="845,445,1001,523" href="home.html" title="My Home Town">
        <area shape="rect" coords="1150,540,1250,600" href="Avadi.html" title="Avadi">
        <area shape="rect" coords="660,570,770,640" href="Thiruninravur.html" title="Thiruninravur">
        <area shape="rect" coords="730,350,810,410" href="Pakkam.html" title="Pakkam">
        <area shape="rect" coords="610,410,690,470" href="Veppambattu.html" title="Veppambattu">
        <area shape="rect" coords="890,300,1030,400" href="Melpakkam.html" title="Melpakkam">
    </map>
  </center>
</body>
</html>
```
### home.html
```
<html>
<head>
  <title>Pattabiram</title>
</head>
<body bgcolor="lightblue">
  <h1 align="center">
    <font color="red"><b>PATTABIRAM</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>My Home Town - Pattabiram</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5">
      Pattabiram is a vibrant suburb located in the western part of Chennai, Tamil Nadu. It is well known for its strategic location, connecting various important parts of the city. The area hosts many residential colonies, educational institutions, and defense establishments like the Air Force Station. Pattabiram has a perfect blend of urban convenience and suburban calm, making it a preferred locality for many families.

      <br><br>

      With easy access to Avadi, Thiruninravur, and other neighboring regions, Pattabiram enjoys strong transport links including suburban trains and buses. Over the years, it has seen significant growth in infrastructure, healthcare, and education, which further enhances its importance in Chennai's urban landscape.
    </font>
  </p>
</body>
</html>

```
### Avadi.html
```
<html>
<head>
  <title>Avadi</title>
</head>
<body bgcolor="lightyellow">
  <h1 align="center">
    <font color="red"><b>AVADI</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>The Industrial and Defense Hub</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5">
      Avadi is a major industrial and residential neighborhood in Chennai, Tamil Nadu. It houses several defense establishments such as the Heavy Vehicles Factory (HVF) and Combat Vehicles Research and Development Establishment (CVRDE). Its strategic importance and employment opportunities have contributed to its rapid urban growth over the years.

      <br><br>

      Avadi is also known for its vibrant community life, educational institutions, parks, and commercial centers. The Avadi Railway Station and excellent road connectivity make it a prime location for those who seek both convenience and opportunities.
    </font>
  </p>
</body>
</html>

```
### Thiruninravur.html
```
<html>
<head>
  <title>Thiruninravur</title>
</head>
<body bgcolor="lavender">
  <h1 align="center">
    <font color="red"><b>THIRUNINRAVUR</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>The City of Temples and Culture</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5">
      Thiruninravur is a historic town located near Chennai, famous for its ancient temples such as the Bhaktavatsala Perumal Temple and Hridayaleeswarar Temple. These architectural marvels make it a spiritual center and a place of deep cultural importance. Pilgrims and tourists alike visit Thiruninravur to experience its spiritual atmosphere.

      <br><br>

      Along with its religious heritage, Thiruninravur has developed into a bustling residential area with good educational institutions and transport connectivity. It offers the perfect blend of culture, spirituality, and modern living.
    </font>
  </p>
</body>
</html>

```
### Pakkam.html
```
<html>
<head>
  <title>Pakkam</title>
</head>
<body bgcolor="lightgreen">
  <h1 align="center">
    <font color="red"><b>PAKKAM</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>The Natural Beauty of Pakkam</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5">
      Pakkam is a peaceful locality situated near Pattabiram, known for its greenery, farmlands, and serene environment. The picturesque surroundings and abundant natural resources make Pakkam a beautiful escape from the bustling city life. It retains its rural charm while slowly developing towards urbanization.

      <br><br>

      Agriculture and local industries are the major occupations here, and residents enjoy a peaceful lifestyle. Pakkam’s proximity to towns like Thiruninravur and Avadi makes it an attractive spot for future growth while preserving its scenic charm.
    </font>
  </p>
</body>
</html>

```
### Veppambattu.html
```
<html>
<head>
  <title>Veppambattu</title>
</head>
<body bgcolor="lightcoral">
  <h1 align="center">
    <font color="red"><b>VEPPAMBATTU</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>The Growing Suburb of Chennai</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5">
      Veppambattu is a rapidly developing suburb located on the Chennai-Arakkonam suburban railway line. Known for its affordable housing options and excellent rail connectivity, Veppambattu is becoming a preferred residential choice for many working professionals and families.

      <br><br>

      With new residential projects, schools, and shopping areas cropping up, Veppambattu is steadily growing into an important suburban center. Its future is promising with more developments on the way, making it a smart choice for homebuyers.
    </font>
  </p>
</body>
</html>

```
### Melpakkam.html
```
<html>
<head>
  <title>Melpakkam</title>
</head>
<body bgcolor="lightpink">
  <h1 align="center">
    <font color="red"><b>MELPAKKAM</b></font>
  </h1>

  <h3 align="center">
    <font color="blue"><b>A Calm and Quiet Neighborhood</b></font>
  </h3>

  <hr size="3" color="red">

  <p align="justify">
    <font face="Georgia" size="5">
      Melpakkam is a serene locality located close to major hubs like Pattabiram and Avadi. It offers a peaceful atmosphere away from the noise and crowd of the city. Surrounded by greenery, Melpakkam provides an ideal setting for those who prefer a calm lifestyle.

      <br><br>

      Though relatively less urbanized, Melpakkam’s strategic location and growing residential interest make it a promising area for future development. It is a perfect blend of village beauty and urban accessibility.
    </font>
  </p>
</body>
</html>

```
## OUTPUT

![1](https://github.com/user-attachments/assets/c5b620f4-6080-4328-9221-ac82d9843f3f)

![2](https://github.com/user-attachments/assets/c24e8c21-f170-4111-b86a-ee46f671d4c1)

![3](https://github.com/user-attachments/assets/21414382-fd5e-4c75-8a01-063a38e16854)

![4](https://github.com/user-attachments/assets/b255d0cc-f7bc-47d9-aa53-43cec4a9a566)

![5](https://github.com/user-attachments/assets/4d4db6fa-bba0-4c9c-8adb-54090ae16443)

![6](https://github.com/user-attachments/assets/7db4239b-5c5a-45c4-a234-5eece9f92cef)

![7](https://github.com/user-attachments/assets/9b47c0eb-ef27-40b6-80e5-6c033e9be0c4)
## RESULT
The program for implementing image maps using HTML is executed successfully.
