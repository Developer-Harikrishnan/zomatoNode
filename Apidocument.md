Page 1
List of city
  >http://localhost:6700/location

List of restaurants 
  >http://localhost:6700/restaurant

restaurants wrt to city 
  >http://localhost:6700/restaurant?state_id=1

quick search data  
  >http://localhost:6700/mealType

Page 2
restaurants wrt to quickSearch 
  >http://localhost:6700/restaurant?meal_id=2

filter
> cuisine filter
  data respect to cuisine and quickSearch 
  >http://localhost:6700/filter/2?cuisine_id=4

> cost filter
  >http://localhost:6700/filter/3?lcost=200&hcost=500
   
> cuisine filter + cost filter 
 data respect to cuisine and cost
  >http://localhost:6700/filter/1?lcost=200&hcost=500&cuisine_id=1


> sort
  >sort low to high in same quickSearch
    >http://localhost:6700/filter/1?lcost=200&hcost=500&cuisine_id=1&sort=1
    >http://localhost:6700/filter/1?cuisine_id=1&sort=1

  >sort high to low in same quickSearch
    >http://localhost:6700/filter/1?lcost=200&hcost=500&cuisine_id=1&sort=-1
    >http://localhost:6700/filter/1?cuisine_id=1&sort=-1


> pagination
    >http://localhost:6700/filter/1?cuisine_id=1&skip=0&limit=2


Page 3
> restaurants details
  >http://localhost:6700/details/1

> Menu of that restaurants
  >http://localhost:6700/menu/1


page 4
> menu items on user selection
  >http://localhost:6700/menuItem

> api to place order
  >http://localhost:6700/placeOrder

page 5
> list all order
  >http://localhost:6700/orders
  >http://localhost:6700/orders?harikrishnanpnair31@gmail.com

Delete order 
> localhost:6700/deleteOrder
 

Update order
 >localhost:6700/updateOrder/62093cfef4e16245da694af4?status=Success