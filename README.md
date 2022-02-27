# Client-Server-Development

# About the Project/Project Title
Grazioso Salvare are seeking a software application that can work with existing data from five animal shelters in the region around Austin, Texas to identify and categorize available dogs that are good candidates for search-and-rescue training. Global Rain has contracted for a full stack development of this application that will include a database and a client-facing web application dashboard, through which users at Grazioso Salvare will access the database.

# Motivation
This project was created to gain experience using MongoDB and Python. This was my first experience with databases.

# Getting Started
•	Open a terminal window and start mongodb
•	Enter credentials to access the database and collections
•	Open a .ipynb file (jupyter notebook) and import animal_shelter.py
•	Create an AnimalShelter object and authenticate using the user credentials from AAC database
•	Use the AnimalShelter object to create, read, update and delete documents
•	Use Dash to create an interactive app using layout and callbacks
•	Include code to query mongodb documents so data is accurate when drop down choices are selected
•	Create the pie graph and interactive map using Dash, plotly, and leaflet (https://dash-leaflet.herokuapp.com/)

# Installation
•	Install MongoDB: https://docs.mongodb.com/manual/installation/
•	Import .csv dataset (from Apporto)
•	Create a user in the ‘admin’ administrationDatabase 
•	Install Dash: https://dash.plotly.com/installation
•	Install any imports from source code that aren’t already

# Usage: App Dashboard

## Starting State

![1 1 starting state datatable](https://user-images.githubusercontent.com/85969866/155901105-46b8af7a-3788-496f-b24b-eeb19d064895.jpg)

![1 2 starting state pie chart](https://user-images.githubusercontent.com/85969866/155901115-80bb2b8f-83ab-46be-8453-f46d6f9c9225.jpg)

![1 3 starting state interactive map](https://user-images.githubusercontent.com/85969866/155901125-52a17ffa-11bc-4706-868c-5a95c20f73d4.jpg)



## Water Rescue

![2 1 water rescue datatable](https://user-images.githubusercontent.com/85969866/155901145-56bcd0ed-9452-47d5-b668-cb520c7cccb5.jpg)

![2 2 water rescue pie chart](https://user-images.githubusercontent.com/85969866/155901154-96207add-6cba-4e37-a92f-11e22186d5ca.jpg)

![2 3 water rescue interactive map](https://user-images.githubusercontent.com/85969866/155901162-d5511e83-e7fc-40e5-b7e0-1a113b537554.jpg)



## Wilderness Rescue

![3 1 wilderness rescue datatable](https://user-images.githubusercontent.com/85969866/155901178-3d1bb0b8-c22d-422d-b978-df5865837b7c.jpg)

![3 2 wilderness rescue pie chart](https://user-images.githubusercontent.com/85969866/155901182-f7784dad-ba38-4be1-905a-73394aff3e54.jpg)

![3 3 wilderness rescue interactive map](https://user-images.githubusercontent.com/85969866/155901189-ad2a26e6-8305-4072-ad9a-90e0c67349d6.jpg)



## Disaster Rescue

![4 1 disaster rescue datatable](https://user-images.githubusercontent.com/85969866/155901201-65a3146e-9114-4dc3-90ae-87bf11748609.jpg)

![4 2 disaster rescue interactive map](https://user-images.githubusercontent.com/85969866/155901206-75d944d8-a138-4b5d-bf25-617855e4e668.jpg)

![4 3 disaster rescue interactive map](https://user-images.githubusercontent.com/85969866/155901217-984d9fc1-d451-46f5-bd8e-8df9743b2e34.jpg)



## Reset

![5 1 reset datatable](https://user-images.githubusercontent.com/85969866/155901230-ce8938c5-1ad8-4a09-9649-2e9f81c62325.jpg)

![5 2 reset pie chart](https://user-images.githubusercontent.com/85969866/155901254-937bc89b-0fee-49d5-8855-56bef0a471c5.jpg)

![5 3 reset interactive map](https://user-images.githubusercontent.com/85969866/155901258-b557cf2b-a4ad-4c40-b48b-baea573d3f55.jpg)



# Usage: Python CRUD

![image](https://user-images.githubusercontent.com/85969866/155901286-c493c215-35ae-4e87-be9a-69c44c3e1a68.png)

![image](https://user-images.githubusercontent.com/85969866/155901291-5dcb2f8a-e717-4a04-9de0-9962f1e71fa2.png)



# Roadmap
The update_many method may be a little confusing and may need to be updated before use. This project only utilized the read_all method. The pie chart is also a little confusing and could be updated. For the water rescue dogs, the query returned only Labrador Retriever Mix as the breed. I think this is an error. 
Returning the update_many method produces an UpdateResult object. Creating a cursor to the documents before updating them isn’t helpful, because the reference doesn’t change, so the cursor still holds the old values. Therefore, I decided to put all of the document id’s that are to be updated into a list. From there I created another list and appended each updated doc by its id. Finally, I returned the list in JSON format.


# Contact
Your name: Matthew Oliphant
