# Sales-anytics-Dashboard

# Tables 
![image](https://github.com/user-attachments/assets/c66e530e-42f1-49c9-8339-ca1b3690448c)

# Key mesures 

## Total sales 
> **Total sales = sum(shipments[Sales])**


>>
![image](https://github.com/user-attachments/assets/ce911345-0226-4e74-938d-b451d68cfb7b)
>>




## Total boxes 
>**Total boxes = sum(shipments[Boxes])**

>>
   ![image](https://github.com/user-attachments/assets/1fe12a26-44e7-47d5-be64-9efc59e21169)

>>

## Total shipments
>**Total shipment = COUNTROWS(shipments)**
>
![image](https://github.com/user-attachments/assets/a66fdc49-8b17-45d2-ab65-98ff568a245a)
>


## Total cost 

> **Total cost = SUM(shipments[cost])**
>
 ![image](https://github.com/user-attachments/assets/77891dbf-442f-41f1-a5f2-12c1be9eeb34)
 >

## Total profit 
>**Total profit = [Total sales]-[Total cost]**
>
![image](https://github.com/user-attachments/assets/46c58259-ef4e-4a3a-aa54-1ca97126c1bc)

>

## Profit%
>**Profit % = DIVIDE([Total profit],[Total sales])**
>
![image](https://github.com/user-attachments/assets/6cab52ff-3366-4ee2-9192-d56375f2d66c)

>
## Low box shippment count (LBS count)
>**LBS COunt = CALCULATE([Total shipment],shipments[Boxes]<50)**
>
![image](https://github.com/user-attachments/assets/af28b565-2450-449c-8fb3-14db80a4c612)
>


## LBS%
>**LBS% = DIVIDE( [LBS COunt] , [Total shipment])**
>
![image](https://github.com/user-attachments/assets/3963c9ea-c884-43d9-a090-5a8330b18f5d)
>


## Month on month chnages 

## Year on year chnages 


