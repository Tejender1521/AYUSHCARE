# AyushCare - Mapping healthcare, one hospital at a time.

A hospital card providing information about one of 7000 Ayush Hospital across India.

![alt text](https://i.ibb.co/HrFjqTQ/hospital-info.jpg)


## Description

AyushCare is healthcare based database designed to make the process of finding hospitals included in Indian Government's "Ayush Hospitals" scheme frictionless. 
The main aim is to document, map and digitalize indian healthcare system. Ayushcare maps various Ayush hospitals across India with the help of Mapbox API. When a user clicks the pointers nearest to their location, they show information cards displaying the phone numbers, addresses, bed vacancies etc of the particular hospitals.

## Getting Started

### Dependencies

 * "bcrypt": "^5.0.1",
 * "dotenv": "^8.2.0",
 * "express": "^4.17.1",
 * "mongoose": "^5.12.4",
 * "nodemon": "^2.0.7"

### Installing

* Download the repository files and folders
```
cd folder/to/clone-into/
git clone https://github.com/AbhinavJaintle/AyushCare
```

### Executing program

* Open two parallel terminals
* Run MongoDB from the backend folder in Terminal 1
```
cd backend
node index.js
```
* Run App.js from the frontend folder in Terminal 2
```
cd frontend
npm start app.js
```

## Working Site

Overview of the map: 

![alt text](https://i.ibb.co/8cFhMgx/Screenshot-2022-07-12-002504.jpg)

Registering/logging in the database: 

![alt text](https://i.ibb.co/zxgws0w/Screenshot-2022-07-12-002547.jpg)

Add more and more hospitals to the map: 

![alt text](https://i.ibb.co/Chx6rRF/Screenshot-2022-07-12-002700.jpg)


## Acknowledgments

* [Smart India Hackathon](https://www.sih.gov.in/)
* [Mapbox API](https://docs.mapbox.com/api/overview/)
