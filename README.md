# week 3
## exercise 2
### 1
![img.png](image%2Fimg.png)
### 2
![img_1.png](image%2Fimg_1.png)
### 3
![img_2.png](image%2Fimg_2.png)
### 4
![img_3.png](image%2Fimg_3.png)
### 5
![img_4.png](image%2Fimg_4.png)
### 6
![img_5.png](image%2Fimg_5.png)
### 7
![img_6.png](image%2Fimg_6.png)
### 8
![img_7.png](image%2Fimg_7.png)
### 9
![img_8.png](image%2Fimg_8.png)
### 10
![img_9.png](image%2Fimg_9.png)
## exercise 2
### 1 select country.name as "country name", airport.name as "airport name"
from airport, country
where airport.iso_country = country.iso_country and country.name = "Iceland";
![img_10.png](image%2Fimg_10.png)
### 2 select airport.name as "airport name"
from airport, country
where airport.iso_country = country.iso_country and country.name = "France" and airport.type = "large_airport";
![img_11.png](image%2Fimg_11.png)
### 3 select country.name as country_name, airport.name as airport_name
from airport, country
where airport.iso_country = country.iso_country and country.continent = "AN";
![img_12.png](image%2Fimg_12.png)
### 4 select elevation_ft
from airport, game
where location = ident and screen_name = "Heini";
![img_13.png](image%2Fimg_13.png)
### 5 select elevation_ft * 0.3048 as elevation_m
from airport, game
where location = ident and screen_name = "Heini";
![img_14.png](image%2Fimg_14.png)
### 6 select name
from airport, game
where location = ident and screen_name = "Ilkka";
![img_15.png](image%2Fimg_15.png)
### 7 select country.name
from airport, game, country
where location = ident and airport.iso_country = country.iso_country  and screen_name = "Ilkka";
![img_16.png](image%2Fimg_16.png)
### 8 select name
from goal, goal_reached, game
where game.id = game_id and goal.id = goal_id and screen_name = "Heini";
![img_17.png](image%2Fimg_17.png)
### 9 select airport.name
from airport, game, goal, goal_reached
where ident = location and game.id = game_id and goal.id = goal_id and screen_name = "Ilkka" and goal.name = "CLOUDS";
![img_18.png](image%2Fimg_18.png)
### 10 select country.name
from country, airport, game, goal, goal_reached
where airport.iso_country = country.iso_country and ident = location and game.id = game_id and goal.id = goal_id and screen_name = "Ilkka" and goal.name = "CLOUDS";
![img_19.png](image%2Fimg_19.png)

# week 4
## exercise 4
### 1 
