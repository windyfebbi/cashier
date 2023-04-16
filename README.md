# Self-Service Cashier Program
# Latar Belakang
This is a simple self-service cashier program for make purchasing transactions, including add items, edit (update) items, delete items, reset transaction, check order, checkout, until payment activities. All of data items are input (type) by customer. For every transactions there will be a discount with applicable terms and conditions. Customer can also choose their preference payment method in last step of the program
# Requirements
1. Customer create id transaction
2. Then, customer input items data like name, qty, and price
3. If there was a mistaken when input, cust can do an update data inc name, qty, and price
4. If customer cancel order, cust can just delete some items or reset transaction. After reset transaction there will be a choice between make new transaction or not
5. After input data, to make sure data input is correct they can check in with check_order
6. Then customer can see the total payment and discount (if exist)
7. Customer choose the payment option
# Flowchart
![cashier flowchart](https://user-images.githubusercontent.com/130646821/232321826-2866dc31-18d7-4ac4-8472-b5a9ed051a02.png)
# Method
Here some method command customer can do during transaction:
1. add_item for add new item
2. update_item for update item
3. delete_item for delete the item
4. reset_trnsct for reset transaction
5. check_order for check the order input
6. checkout for continue to total payment and see the discount (if exist)
7. payment for choose payment method
# Test Case
