# Tap News 

CS503 Spring 2019 full stack engineering project


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


## QA
#!/bin/bash
fuser -k 3000/tcp
fuser -k 5000/tcp
