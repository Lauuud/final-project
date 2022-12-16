# Inventory management
#### Video Demo:  <https://www.youtube.com/watch?v=Ahqu-PJAJes>
#### Description:

1. This tool initially created by myself to keep track of the orders, stock situation, historic price of my products and other data.
I used google sheet formula, app sheet and app script together to make possible. (Sorry about the Chinese column names, if I change them, it would took a lot of effort to change other part of the script.)

2. Fistly, I created an mobile application with appsheet and google sheet. It is the database that I used for store the neccessary
data for my program.[Database for program](%E4%BA%A7%E5%93%81%E5%BA%93%E5%AD%98.xlsx). But that is not enough, there are lots of
other problems. For examples, the price of my products change everyday, and I have 100 plus products, it would be very hard to
to change it manually. So I use created this app script[change price and cost of my products](Copy20AEE595BBE6A5BAE598BCE48A97E4B7A0%25BC.json). Which would run every night, changing the price of the products based on the
today's orders. I also want to keep track of the price of every products and the quantity sold every day. Therefore, I created this app script[transfer data](Copy209BE6B0BAE59888E58B802CBCE5AA8820orders88EF8Cde-formulaE48A97E6B685%25A5.json) to transfer my today's data to these two google sheets.[google sheet that store the historic price of every products](Copy%20of%20%E4%BB%B7%E6%A0%BC%E5%8E%86%E5%8F%B2.xlsx)and [google sheet that store the historic change of stock of every products](Copy%20of%20%E5%BA%93%E5%AD%98%E5%8E%86%E5%8F%B2.xlsx).