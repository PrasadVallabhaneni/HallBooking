# HallBooking

API Documentation

1. Create Hall: POST- http://localhost:3002/hall
ex:{
    "name":"Hall-3",
    "amenities":["Ac","Refregirator","Swimming Pool"],
    "price":1000
}

2. View Halls: GET-http://localhost:3002/Halls

3. Create Order: POST- http://localhost:3002/order
ex: {
    "hallId":3,
    "customer":"Person3",
    "start":"12/16/2020",
    "end":"12/20/2020"
}

4. view orders: GET-http://localhost:3002/Orders
