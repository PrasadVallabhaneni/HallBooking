# HallBooking

API Documentation

1. Create Hall: POST- https://hall-b00king.herokuapp.com/hall
ex:{
    "name":"Hall-3",
    "amenities":["Ac","Refregirator","Swimming Pool"],
    "price":1000
}

2. View Halls: GET-https://hall-b00king.herokuapp.com/Halls

3. Create Order: POST- https://hall-b00king.herokuapp.com/order
ex: {
    "hallId":3,
    "customer":"Person3",
    "start":"12/16/2020",
    "end":"12/20/2020"
}

4. view orders: GET-https://hall-b00king.herokuapp.com/Orders
