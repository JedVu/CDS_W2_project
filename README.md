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
 
 ![image](https://user-images.githubusercontent.com/63096813/114338224-d400bc00-9b7c-11eb-8999-03b2ab5d41f2.png)

 
9.	Create Products table:
 
 ![image](https://user-images.githubusercontent.com/63096813/114339824-5474ec00-9b80-11eb-92fa-8f05823ec427.png)


10.	Create Class Product to store product attributes, use product_sku as ID
 
 ![image](https://user-images.githubusercontent.com/63096813/114338248-e2e76e80-9b7c-11eb-96a0-7fee3e11b3d7.png)


11.	Create PRODUCT_SET and function def can_add_to_cat_set_product(product_sku,save=False) check product imported to database or not
 
 ![image](https://user-images.githubusercontent.com/63096813/114338257-e975e600-9b7c-11eb-967a-381ac11c644d.png)


12.	Create function def get_product(tiki_products,save_db=False) to import data row by row to database
 
 ![image](https://user-images.githubusercontent.com/63096813/114338270-eed33080-9b7c-11eb-90ab-591fed477b6d.png)


13.	Import to database… wait and wait and more coffee
 
 ![image](https://user-images.githubusercontent.com/63096813/114338277-f2ff4e00-9b7c-11eb-80ae-24fbba597569.png)


14.	WHAT THE HELL IS GOING ON!!!! SOMETHING HAPPENNED! OH, It only affects on Chrome output printing.

 ![image](https://user-images.githubusercontent.com/63096813/114338291-fabef280-9b7c-11eb-9427-3b6a912900a6.png)

Actually we have another solution to do bulk import data to SQL in short time but we want to follow the project structure to check duplication and import data row by row and get real NIGHTMARE.

Wow, after 32m, all products imported to database
 
 ![image](https://user-images.githubusercontent.com/63096813/114338303-03172d80-9b7d-11eb-9bbb-ca3950d35eb2.png)

15.	What is the most expensive product for all category?
 
 ![image](https://user-images.githubusercontent.com/63096813/114338324-0a3e3b80-9b7d-11eb-9b42-ce0a404d38d3.png)


16.	What is the most expensive item for each category?
 
 ![image](https://user-images.githubusercontent.com/63096813/114338335-0f02ef80-9b7d-11eb-86de-a94d06d1a875.png)

 
17.	Which category contains the most items?
 
 ![image](https://user-images.githubusercontent.com/63096813/114338345-13c7a380-9b7d-11eb-8baf-d0ae688601ed.png)

 ![image](https://user-images.githubusercontent.com/63096813/114338353-16c29400-9b7d-11eb-977f-07f0f7d83288.png)


18.	Which category/product has the highest reviews or ratings ...?


 
19.	This week project we learned:
          - read code, understand code, copy, paste and edit code.
          - print to view result first
          - Chrome addon to keep Colab run but sometimes Colab give us a warning board to verify us is human or bot.

20.	An error when we forgot some letter when coding

 ![image](https://user-images.githubusercontent.com/63096813/114338370-22ae5600-9b7d-11eb-8512-5608c62574d2.png)

