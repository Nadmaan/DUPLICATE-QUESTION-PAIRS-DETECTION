# DUPLICATE QUESTION PAIRS DETECTION 
Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

# Steps for end-to-end solution 
**1. Importing Dependencies**
![Importing dependencies](https://user-images.githubusercontent.com/83595856/185223226-25649cb4-843c-4fa0-b684-1e8545758bbc.jpg)

**2. Data Visualization**
![visualize the data](https://user-images.githubusercontent.com/83595856/185223934-6894cc25-05fd-4904-8bc4-3fa4d3192e9e.jpg)

**3. Data Preprocessing**
 ![preprocess-1](https://user-images.githubusercontent.com/83595856/185224918-5710cf4a-7301-4c05-8fac-14cb1ca35787.jpg)
 ![preprocess-2](https://user-images.githubusercontent.com/83595856/185225018-0a2ee90a-c7f9-438b-80e9-d359e95b380b.jpg)
![preprocess-3](https://user-images.githubusercontent.com/83595856/185225093-db4b3699-3d01-476b-87a7-10b197c0b20e.jpg)

 **4. Text Vectorization using Count vector(Bag of word Model)**
 ![BOW](https://user-images.githubusercontent.com/83595856/185225466-398ec8ad-90d3-4042-9621-1d8d274fa076.jpg)
 
**5. XGBoost Model with Accuracy Score,Precision score and Recall score**
![XBBoost Model ](https://user-images.githubusercontent.com/83595856/185226339-37084ead-8a6a-4502-a962-f8cdebe2850c.jpg)
![XGBoost precision ](https://user-images.githubusercontent.com/83595856/185226413-121c20ca-8dfa-4703-ab80-58f7d2fd9d04.jpg)

**6. Building the web app**

Query point generation 
![Query point ](https://user-images.githubusercontent.com/83595856/185227778-41560418-52c6-438c-afdf-972138816803.jpg)

Saving the Model
![Pickle to save the model](https://user-images.githubusercontent.com/83595856/185228221-54db4347-abad-4176-a63c-9920b2f1ea69.jpg)

App Making 
![streamlit app_main](https://user-images.githubusercontent.com/83595856/185228330-5affbd01-ade6-40f8-a4db-59b180e474ee.jpg)

Heruko Deployment
![Heruko Interface](https://user-images.githubusercontent.com/83595856/185228850-fa7d8593-9796-412e-b5c7-1202de06519b.jpg)

**7. APP Link**
https://nadmaan-dup-ques.herokuapp.com/
![App in action ](https://user-images.githubusercontent.com/83595856/185229682-b6575d8b-824d-4502-bf93-575c6d6e41df.jpg)









