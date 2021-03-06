# paypay-sample-ecommerce-backend-java

[![License](https://img.shields.io/:license-apache-orange.svg)](https://opensource.org/licenses/Apache-2.0)
[![Language grade: Java](https://img.shields.io/lgtm/grade/java/g/paypay/paypay-sample-ecommerce-backend-java.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/paypay/paypay-sample-ecommerce-backend-java/context:java)
[![Maintainability](https://api.codeclimate.com/v1/badges/50e89180164f39e1d933/maintainability)](https://codeclimate.com/github/paypay/paypay-sample-ecommerce-backend-java/maintainability)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/b2742c69c04540a988002f31c644f03b)](https://www.codacy.com/gh/paypay/paypay-sample-ecommerce-backend-java/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=paypay/paypay-sample-ecommerce-backend-java&amp;utm_campaign=Badge_Grade)
[![BCH compliance](https://bettercodehub.com/edge/badge/paypay/paypay-sample-ecommerce-backend-java?branch=master)](https://bettercodehub.com/)

This is a sample ecommorce application using PayPay's Java SDK. 

It creates QR code link and checks the status of the payment.

### Configurations

update the API Key and Secret with actual values in application.properties file.
Replace your front end URL in the cors.urls property.
```properties
cors.urls=http://localhost:8080
API_KEY=API_KEY
API_SECRET=API_SECRET
```

## How to Run the API Server

```sh
$ ./gradlew bootRun
```

You should now have the API server running on http://localhost:5000

Note: To change the port number update the below property in application.properties

```properties
server.port=5000
```
