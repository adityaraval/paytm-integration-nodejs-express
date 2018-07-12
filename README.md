# Paytm Payment Gateway Integration With NodeJS & Express


Simple explanatory way to use Paytm Payment Integration with NodeJS with Express with minimal dependancies.

### Node Packages Used
* [ejs] - HTML Templating Engine!
* [express] - Http web server!
* [CORS] - CORS is a node.js package for providing a Connect/Express middleware that can be used to enable CORS with various options..
* [dotenv] - Environment config!
* [shortid] - generate unique short IDs
* [body-parser] - Express Middleware..

### ENV Setup
Create .env file as below.

```sh
MID=**MID Given By Paytm Staging Credentials**
PAYTM_MERCHANT_KEY=**PAYTM_MERCHANT_KEY Given By Paytm Staging Credentials**
WEBSITE=WEBSTAGING
CHANNEL_ID=WEB
INDUSTRY_TYPE_ID=Retail
PAYTM_FINAL_URL=https://securegw-stage.paytm.in/theia/processTransaction
CALLBACK_URL=http://localhost:4000/paywithpaytmresponse
PORT=4000
```



### Installation
Install the dependencies and devDependencies and start the server.

```sh
$ cd paytm-integration-nodejs-express
$ npm install
$ npm start
```

### STEPS
* Open below url in browser!
http://localhost:4000/paywithpaytm?amount=10

* You will be redirected to the payment page of paytm,use this staging credentials to login
Mobile no=7777777777,
OTP=489871

* After you login with the staging credentials you will be logged in and once you will click Pay Now button,you will be redirected to below response page with proper payment summary.
http://localhost:4000/paywithpaytmresponse

License
----

MIT


**Free Software, Hell Yeah!**


