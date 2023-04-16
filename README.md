# Self-Service Cashier Program
# Background
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
1. Add new item
![image](https://user-images.githubusercontent.com/130646821/232322406-cf914cd9-410a-444b-911f-4be07d987def.png)
2. Delete item
![image](https://user-images.githubusercontent.com/130646821/232322542-da072c03-9e2f-498f-bc9b-da70a9cf0582.png)
3. Update item
![image](https://user-images.githubusercontent.com/130646821/232322706-edd7ed12-ad32-4491-bcd1-68b10b3f57f6.png)
4. Reset transaction
![image](https://user-images.githubusercontent.com/130646821/232322828-add73fd7-57c2-4008-97e6-70ebeb76db09.png)
5. Check order
![image](https://user-images.githubusercontent.com/130646821/232323037-ec5924ad-df07-4f2a-93f8-f4c0fa8d2036.png)
6. Checkout
![image](https://user-images.githubusercontent.com/130646821/232323064-e9376f1c-85eb-4bee-9987-862b72c88cd3.png)
7. Payment
![image](https://user-images.githubusercontent.com/130646821/232323105-f5d02ee0-f534-4b52-a382-d9eeae2195e1.png)
