---
layout: post
title: Renderizado Exterior
tags: automation python pandas selenium marketing adds


---
Renderizaciones Exteriores

##### Renderizaciones Exteriores

in my 3d printing business i had to post multiple adds for all my products online
doing this manually would take a lot of time, and i could  do manual mistakes

##### solution

find a way to atumatically post the adds with a program

##### idea

i can store all my data in a file (in this case i chose excel to take advantage of the grid properties and structure )
with python i can read the file , store the info in a add_object and make an list of add_objects
now with the list of objects i can load the information to the web with selenium

#### DEMO
i made a demo (in spanish) of me running the program (note 0 profesional video but gets the job done )



<img  width="50%" height="50%" src="./../assets/posts/Exteriores/3_24 - Foto (1).jpg">
<img  width="50%" height="50%" src="./../assets/posts/Exteriores/BELEN 2_16 - Foto.jpg">
<img  width="50%" height="50%" src="./../assets/posts/Exteriores/BELEN 2_17 - Foto.jpg">
<img  width="50%" height="50%" src="./../assets/posts/Exteriores/Fachada frontal 1.jpg">
<img  width="50%" height="50%" src="./../assets/posts/Exteriores/San Vicente_1 - Photo.jpg">
<img  width="50%" height="50%" src="./../assets/posts/Exteriores/Vistas1_7 - Foto.jpg">
##### requierments 

* download the latest chrome browser => https://chromedriver.chromium.org/downloads
* download the project from my github => [github_link](https://github.com/IvanWeissVanDerPolGH/automated-posting)
* download the requierments for the project


### step 1 setup your own credentials for tha pages in the excel

![image](./../assets/posts/autoposter/excel_users.png)

### step 2 add your products in the products tab 
![image](./../assets/posts/autoposter/excel_products.png)
### step 3 run auto poster.py 
![image](./../assets/posts/autoposter/auto_poster_finished_reading_excel.png)


### step 4? it runs  and you can watch as it is posting the adds

![image](./../assets/posts/autoposter/test_hendyla.png)

### in total i posted 3 pages of adds for my actual business 

![image](./../assets/posts/autoposter/resultado_en_hendyla.png)
