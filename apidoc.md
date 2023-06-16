# Flipkart

//Page 1

- List of fashion types
  http://localhost:9120/fashion

- List of Electronics types
  http://localhost:9120/electronics

- List of Home Products types
  http://localhost:9120/home

- List of Beauty-toys types
  http://localhost:9120/beauty

- List of vehicles types
  http://localhost:9120/vehicles

- List of quick search
  http://localhost:9120/quicksearch

//Page2

- products wrt category
  http://localhost:9120/filter/2

- products wrt category + cost
  http://localhost:9120/filter/2?lcost=7000&hcost=20000

- products wrt category + brand
  http://localhost:9120/filter/3?filterId=1

- products wrt category + type
  http://localhost:9120/filter/5?filterId=15

- products wrt category + color
  http://localhost:9120/filter/2?filterId=2

//page 3

- details of product
  http://localhost:9120/details/10

//Page 4

- details of product selected
  http://localhost:9120/productDetails
  {"id":[4,8,21]}

- place order
  http://localhost:9120/placeOrder

//Page 5

- List of all the orders
  http://localhost:9120/orders

- Update orders details
  http://localhost:9120/updateOrder
  {
  "\_id":"648c7effb96458384f7d4835",
  "status":"Out for delivery"
  }

- Delete Orders
  http://localhost:9120/deleteOrder
  {"\_id":"648c8025b96458384f7d4836"}
