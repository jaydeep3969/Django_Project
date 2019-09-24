# Django_Project
Beginner Level Django Rest API


**Task Information :**

>Make a Django REST API

A. Models :

  1.Company 
  - Name
  - Phone Number

  2.Catalog
  - Name
  - Number Of Pieces
  - Per Piece Price

  3.User
  - Name
  - Contact
  - Age
  - DOB
  - Mail


B. Relationships:
  - Company can have multiple catalogs and multiple users
  - One User can have only one company
  - One Catalog can have only one company

C. URLS : 
  - api/users/
  - api/companies/
  - api/catalogs/
  - api/companies/{id}/catalogs

D. Response Format :
  - Comapny and User - All Fields
  - Catalog - All fields + all details of company + dynamic total price (no. of pcs * per pc. price)
