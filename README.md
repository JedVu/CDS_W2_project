# CDS_W2_project
Scrape all tiki product



1.	Choose 3 categories to scrape:

 ![image](https://user-images.githubusercontent.com/63096813/114338014-65236300-9b7c-11eb-98b5-674eb7c98f7b.png)

2.	Get all categories in 3 main_categories, we have 180 categories

 ![image](https://user-images.githubusercontent.com/63096813/114338085-8ab06c80-9b7c-11eb-9107-be6b29b1418c.png)
 
 ![image](https://user-images.githubusercontent.com/63096813/114338124-9734c500-9b7c-11eb-9995-ff7ca7bc234d.png)

 
3.	Find lowest_sub_categories
 
 ![image](https://user-images.githubusercontent.com/63096813/114338132-9c920f80-9b7c-11eb-8fce-f3c5ab09500e.png)

 
4.	Build tupple list with ID and base_urls to prepare all urls to scrape products
 
 ![image](https://user-images.githubusercontent.com/63096813/114338154-a582e100-9b7c-11eb-82e1-b48ccbe6a6e4.png)

 
5.	Function: def extract_tiki_info(parent_id, url) we add key parend_id to product dictionary
 
 ![image](https://user-images.githubusercontent.com/63096813/114338162-aca9ef00-9b7c-11eb-8b7e-993b34add2f7.png)


6.	Edit function def scrape_tiki_team(base_urls)
 
 ![image](https://user-images.githubusercontent.com/63096813/114338185-bcc1ce80-9b7c-11eb-96a4-63d17b769b3e.png)

 
7.	Enjoy many cups of coffee with tiki web scraping
 
 ![image](https://user-images.githubusercontent.com/63096813/114338203-c5b2a000-9b7c-11eb-93c4-7c96f4824f14.png)


8.	A FEW MOMENT LATER… BOOM! We have 11032 products
 

 
9.	Create Products table:
 

 
10.	Create Class Product to store product attributes, use product_sku as ID
 

 
11.	Create PRODUCT_SET and function def can_add_to_cat_set_product(product_sku,save=False) check product imported to database or not
 

12.	Create function def get_product(tiki_products,save_db=False) to import data row by row to database
 

13.	Import to database… wait and wait and more coffee
 

 

14.	WHAT THE HELL IS GOING ON!!!! SOMETHING HAPPENNED!

 

Actually we have another solution to do bulk import data to SQL in short time but we want to follow the project structure to check duplication and import data row by row and get real NIGHTMARE.
	Wow, after 32m, all products imported to database
 

 
15.	What is the most expensive product for all category?
 

 
16.	What is the most expensive item for each category?
 

 
17.	Which category contains the most items?
 
 

18.	Which category/product has the highest reviews or ratings ...?


 
19.	This week project we learned read code, understand code, copy, paste and edit code. Chrome addon to keep Colab run but sometimes Colab give us a warning board to verify us is human or bot.

20.	An error when we forgot some letter when coding

 
