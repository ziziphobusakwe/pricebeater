# Price Beater

### Overview

- Dynamically updates the price of products for price-beater-subscribed seller on TakeAlot Market Place based on price changes by competitors selling the same product. 

    - recieves webhook notifications from TakeAlot about price changes to product
    - calculates 'response price' based on price changes by competitors
    - updates price of product, for seller, to response price 

### Technical (AWS) Solution View
![Technical (AWS) Solution View](docs/assets/price-beater-end-to-end-solution.drawio.svg)