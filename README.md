# Tap New 

Bit Tiger CS503 full stack engineering project


- Implemented a data pipeline which monitors, scrapes and dedupes latest news. (MongoDB, Redis, RabbitMQ, TF-IDF)
- Built a single-page web application for users to browse news (React, Node.js,
RPC, SOA, JWT);
- Implemented a click event log processor which collects users’ click logs, then
updates a news preference model for each user (NLP);
- Designed and built an offline training pipeline for news topic modeling
(Tensorflow, DNN, NLP);
- Deployed an online classifying service for news topic modeling using the trained
model.

### Skills:
JavaScript, Python, React, Node.js, Express, Redis, MongoDB, Tensorflow, NLP.

### Tools:
Linux, VirtualBox, Git, Atom, Postman.




## 1. API
### User Statistics Data
- [x] Total Users {"total users" : 1000}
- [ ] New Users (Today) {"dailyNewUsers" : 30}
- [x] Active Users (Today) {"dailyActiveUsers" : 200}
- [ ] Average Usage Time

### User Trend
- [ ] New User 
```json
{ 
    "-6" : 20,
    "-5" : 50,
    "-4" : 34,
    "-3" : 20, 
    "-2" : 90,
    "-1" : 74,
    "0" : 110
}
```
- [x] Active User
```json
{ 
    "-6" : 74,
    "-5" : 110,
    "-4" : 50,
    "-3" : 34, 
    "-2" : 20,
    "-1" : 90,
    "0" : 74
}
```

### User Device
- [x] {"IOS" : 200, "IPHONE" : 300, "Others" : 100}

### User News Category
- [x] {"technology" : 50, "music" : 150, "others" : 50}

### User Active Time distribution (24 hours)
- [x] {"00" : 20, "01": 30, ... "23" : 40}

## 2. data stream

web server/ client
            server
backend_rpc

operations


## Deployment


## QA
#!/bin/bash
fuser -k 3000/tcp
fuser -k 5000/tcp
