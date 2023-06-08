# Project 1 Revisited
### Edmar Dos Santos
### edmardossantos85@gmail.com
 
![LR Coefficients](https://github.com/BrazilianKing/Project-1-Revisited/assets/123523010/36532f61-8d89-4f9a-b0f2-b6d9db0be598)

## 3 Most Impactful Coefficients
- Outlet_Type_Supermarket_Type 3: This supermarket must be the type that brings in the most business. 
- Item_Type_Seafood: This type of product must bring in the most sales out of all food types
- Outlet_Type_Supermarket_Type 1: This must be the market that brings in the second most right before 'Type 3'
 
![feature importance graph](https://github.com/BrazilianKing/Project-1-Revisited/assets/123523010/0886b402-de5e-4a03-b4a7-15e7868b12dc)

## 3 Most Impactful Features
- Item MRP: Makes sense that Material requirement planning would be the most import feature due to the immense amount of products going in and out of the outlets. 
- Outlet_Type_Grocery_Store: This can greatly benefit or greatly hinder an Outlet due to the type of product they are selling. For example it can be an outlet for high end products or an outlet for already lower end products or products that are produced in mass.
- Item_Visibility: Where items are place have a great advantage. For example those items that are put on the front window of the store with the lights shinning on them will more than likely have a high volume in sales vs those other items in the back of the store.

![SHAP bar](https://github.com/BrazilianKing/Project-1-Revisited/assets/123523010/11a841a2-f9eb-401d-9500-a105008e196b)

- Both SHAP bar graph and Feature importance graph have the same top 5 features but "Item_visibility" and "Outlet_Type_Supermarket_Type3" are in difference positions

![SHAP Dot](https://github.com/BrazilianKing/Project-1-Revisited/assets/123523010/650305c7-1444-49d7-af3e-793bfa3fd1fb)

## 3 Most Important Features
- Item MRP
- Outlet_Type_Grocery Store
- Outlet_Type_Supermarket_Type3


![red-blue bar](https://github.com/BrazilianKing/Project-1-Revisited/assets/123523010/bd0669e2-21a7-4305-b80e-5780dafb1e65)

- Item_MRP has the most impact on pushing the target higher while the Outlet_Type_Grocery Store being equal to 0 actually increases our target. Item_Visibility also has an impact on pushing the target higher. 

![Screenshot 2023-06-08 181933](https://github.com/BrazilianKing/Project-1-Revisited/assets/123523010/c9c4fd77-ee02-437a-b3fa-638f69a38e1d)

- When the Outlet_Type_Grocery Store is equal to 0 it increases the target and Outlet_Type_Supermarket Type 3 decreases our target when equal to 0. 
- So this also tells me if Supermarket Type3 were to equal 1 it would in fact increase our target.

![Screenshot 2023-06-08 183206](https://github.com/BrazilianKing/Project-1-Revisited/assets/123523010/8b925552-d376-4501-bcb2-36c316a6e241)

- This graph is showing sample order similarities and confirms previous statements on the graphs prior to this one.
