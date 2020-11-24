
Example request:
``` JSON
Accept: application/json
Content-Type: application/json
POST/orders
curl -H "Content-Type: application/json" -X POST -d'{
   "mealType":"lunch",
   "mealCat":{
  	"main":"burgerMeal",
  	"burger":{
     	"pattyType":"veggie",
     	"pattyQty":2,
     	"pattyWeightG":300,
     	"pattyCook":"medium",
     	"bunType":"wholewheat",
     	"condiment1":"ketchupandmustard",
     	"condiment2":"guacamole",
     	"topping1":"lettuceandtomatoes",
     	"topping2":"none",
     	"topping3":"onions",
     	"topping4":"jalapenos"
  	},
  	"sides":{
     	"side1":{
        	"type":"onion rings",
        	"size":"large"
     	},
     	"side2":{
        	"type":"coleslaw",
        	"size":"small"
     	}
  	},
  	"drink":{
     	"type":"7-Up",
     	"size":"small",
     	"ice":"yes"
  	} 
```
Example response
200 OK

Example request:
Accept: application/json
Content-Type: application/json
POST/orders

``` JSON

curl -H "Content-Type: application/json" -X POST -d'{
   "mealType":"lunch",
   "mealCat":{
  	"main":"burgerMeal",
  	"burger":{
     	"pattyType":"veggie",
     	"pattyQty":3,
     	"pattyWeightG":300,
     	"pattyCook":"medium",
     	"bunType":"regular",
     	"condiment1":"ketchupandmustard",
     	"condiment2":"guacamole",
     	"topping1":"lettuceandtomatoes",
     	"topping2":"none",
     	"topping3":"onions",
     	"topping4":"jalapenos"
  	},
  	"sides":{
     	"side1":{
        	"type":"potatochips",
        	"size":"large"
     	},
     	"side2":{
        	"type":"coleslaw",
        	"size":"small"
     	}
  	},
  	"drink":{
     	"type":"7-Up",
     	"size":"small",
     	"ice":"yes"
```
Example response
400 Bad request. 

