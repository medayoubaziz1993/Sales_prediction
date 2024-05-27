# Sales_prediction
The project will be a sales prediction for food items sold at various stores. 
The data compconsists of 8523 entries and 12 columns : 

- Item_Identifier : Unique product ID
- Item_Weight : Weight of product
- Item_Fat_Content : Whether the product is low fat or regular
- Item_Visibility : The percentage of total display area of all 
                    products in a store allocated to the particular product          
- Item_Type : The category to which the product belongs               
- Item_MRP : Maximum Retail Price (list price) of the product                 
- Outlet_Identifier : Unique store ID       
- Outlet_Establishment_Year : The year in which store was established
- Outlet_Size : The size of the store in terms of ground area covered               
- Outlet_Location_Type : The type of area in which the store is located    
- Outlet_Type :  Whether the outlet is a grocery store or some sort of supermarket            
- Item_Outlet_Sales : Sales of the product in the particular store. This is the target variable to be predicted.

Since it's my first project i tried all that i know : 

here's the correlation between the columns 
![téléchargement (5)](https://github.com/medayoubaziz1993/Sales_prediction/assets/162934368/b2530693-53c4-4b63-83ca-ebeaed9f4874)

![téléchargement (6)](https://github.com/medayoubaziz1993/Sales_prediction/assets/162934368/af59712b-365a-4172-8596-b0b4ac1f322b)

There's a positive correlation between the itm MRP and our target wich is Item outlet sales 

![téléchargement (7)](https://github.com/medayoubaziz1993/Sales_prediction/assets/162934368/bc8c6bd0-1d7d-45a3-8ec2-c8a345c2f6c3)

Since we exploring the data we can see , first of all , there's some missing data that we gonna impute with the adequat startegy . The second thing that we can assume is that the medium size is the one with the most sales 

We can say the same for the supermarket type 3  : 

![téléchargement (9)](https://github.com/medayoubaziz1993/Sales_prediction/assets/162934368/9a05b750-0ccb-473b-af07-ee88e0629513)
	
	
After some cleaning and data engineering with the data that we have , i tried the data on many of the known models but i failed to find the adequat model 

![Capture d'écran 2024-05-27 205323](https://github.com/medayoubaziz1993/Sales_prediction/assets/162934368/73b28d8f-4c2d-4057-a405-c5083c8fb7b2)
	
I tried to tune many models so i can find one with acceptable results but unfortunately i cannot propose any of them to the stackholder , here's the results : 

![Capture d'écran 2024-05-27 205828](https://github.com/medayoubaziz1993/Sales_prediction/assets/162934368/b175cd42-ba9a-4e99-b3d0-ad9495c8c4c0)
![Capture d'écran 2024-05-27 205807](https://github.com/medayoubaziz1993/Sales_prediction/assets/162934368/5ea34d4b-b924-454a-860b-2662925e440a)
![Capture d'écran 2024-05-27 205841](https://github.com/medayoubaziz1993/Sales_prediction/assets/162934368/b03fde09-0ce3-4eb7-ad5e-218a52a9ceb8)

and here's the least bad one : 


![Capture d'écran 2024-05-27 205850](https://github.com/medayoubaziz1993/Sales_prediction/assets/162934368/7357d950-f2af-4763-b3f0-a8761baa2517)
