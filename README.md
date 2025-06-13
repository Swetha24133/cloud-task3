# cloud-task3

COMPANY CODTECH IT SOLUTIONS

 NAME: SWETHA ATLURI

 INTERN ID: CT04DL970

 DOMAIN: CLOUD COMPUTING

 DURATION: 4 WEEEKS

 MENTOR: NEELA SANTOSH
 
# 🌐 Multi-Cloud Architecture Demo

This project demonstrates a basic **multi-cloud architecture** setup where services interact across **two cloud platforms**, showcasing **interoperability** in a distributed cloud system. The frontend is hosted on one platform (e.g., local server or AWS/GCP), and the backend uses **Firebase Realtime Database** as a lightweight, scalable backend service.

## ✅ Project Objective

The primary goal of this task is to simulate and visualize a basic **multi-cloud integration**, where frontend services hosted in one cloud environment fetch and display data from a backend hosted in another cloud platform.

## 🛠️ Technologies Used

- **HTML5 & CSS3** – For building the frontend interface.
- **JavaScript (Fetch API)** – To make API requests and retrieve data from Firebase.
- **Firebase Realtime Database** – Serves as the cloud-hosted backend database.
- **Live Server / Python HTTP Server** – To run the project locally without CORS issues.

## 🔗 Firebase Backend URL

The project fetches data from the following Firebase Realtime Database endpoint:

https://cloud-backend-task3-default-rtdb.firebaseio.com/message.json


Ensure this endpoint is accessible publicly by updating your Firebase database rules.

## ⚙️ How It Works

1. The HTML page is opened using a local server (not directly as a `file:///` path).
2. A fetch request is made to the Firebase Realtime Database.
3. The Firebase backend responds with a message.
4. The frontend dynamically displays the message on the page.

## 🔒 Firebase Security Rules

To enable public read access (for demonstration only), set your Firebase rules as:

```json
{
  "rules": {
    ".read": true,
    ".write": false
  }
}

##OUTPUT


