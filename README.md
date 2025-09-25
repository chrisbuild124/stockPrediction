# INDEX

## Planning
### Goals: 
- Use important/popular frameworks including AI/ML frameworks
- Use Unittests
- Display on plot (either matplotlib, plotly, etc)
- Use API's to retrieve information
- Store in MongoDB database
- Require a login based on gmail account to authenticate correct database
- Stretch: Use AWS to send notifications via SMS

### Visualization packages/modules (1-2):
1. matplotlib
2. plotly
3. seaborn

### ML Models (1-2):
1. scikit-learn
2. xgboost
3. statsmodels

### Deep Learning (1-2):
1. tensorflow/pytorch
2. prophet

### Rules:
- Predict next 1 month stock price (1 week intervals)
  - Graph this
- Store this into mongoDB for caching
- Keep login using .env file
- Stretch - Upload to AWS, have AWS check each hour
  - If >= 5% difference, alert via SMS

### Specifics:
- Start w/ connecting to MongoDB
- Then create a .env to connect
- Create regular expressions to manage input
- Create login feature with google to authenticate user to mongoDB
- Create ML model and store data into Python
  - After model is complete, store into MongoDB
- Display data
- Stretch - AWS alerts
