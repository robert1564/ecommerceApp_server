# ecommerceApp_server

Back-End:
  - NodeJS and ExpressJS

Database:
  - MongoDB

Front-End:
  - React and Redux

## Stages of development:

  - Back-End side:
      - creating request and response objects;
      - creating asynchronous functions;
      - creating models for documents that will be saved in the database;
      - route creation;
      - JWT (JSON Web Token) for authentication;
      - middleware to secure requests that was sent to server;
      - developing several APIs to control various requests, e.g: post request for creating a new user, get request for displaying products on the page, patch for             updating the shopping cart, and much more;
          - I will develop and model these APIs using good practices;
      - secure connection of the back-end with the front-end using different call protocols;

### Devops tools:
  - Stripe API, for consuming payment APIs from various third-party services;
  - Create a secure CI pipeline (continuous integration) to Google Cloud Platform using Travis CI;
  - Using the Google Cloud app engine;
  - Use Google Cloud storage to store all static files used in the application;
  - I will create containers using Docker;
  - CI deployment to Docker Ops;
  - Creating different containers for client and server in Docker Hub;

### App features:
  - Possibility to create / authenticate a new user;
  - Possibilities to operate the site in different ways depending on the type of user admin / user;
  - The admin will have at his disposal a dashboard in which he can view the income he has accumulated, 
    the number of active products on the site, the overall rating received from users and the number of 
    products returned by buyers. Also from here you will be able to add new products, you can view the 
    existing ones;
  - Adding / removing products in / from the shopping cart
  - Possibility to purchase products using a shopping card
  - All card payments will go directly to the Stripe account where the admin will be able to view the orders made

Documentation in progress:
[Aplicatie Ecommerce.pdf](https://github.com/robert1564/ecommerceApp_server/files/8925989/Aplicatie.Ecommerce.pdf)
