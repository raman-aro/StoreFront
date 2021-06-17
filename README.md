# StoreFront
Storefront is a mobile app that allows shoppers to easily find the shortest path between products they are looking for in stores, and store owners the ability to easily add their product selection to the store layout for customers to search! This minimizes the risk of exposure to COVID for both shoppers and store owners, while also saving them time and money.

This project made use of a number of **Firebase** services, including: <br>
* **Authentication** for owner login
* **Cloud Functions** as POST endpoints for updating the store attributes in Firestore DB (Update Store Layout or Add/Remove Products) 
* **Storage** for storing the images of the products the owner adds - the image URL is then stored in the Firestore db as an attribute of the product associated with it
* **Firestore** for storing the store information per owner (this includes store layout and all product information ie. location, quantity, image URL, name, etc)

Please watch the video below which also provides an in-depth explanation of the application and its features:

## Video Demonstration
https://www.youtube.com/watch?v=TuHlVirlkd8&feature=youtu.be
<br>
<br>
[![StoreFront Demo](http://img.youtube.com/vi/T1N5sZI_OZ4/0.jpg)](https://www.youtube.com/watch?v=T1N5sZI_OZ4)

