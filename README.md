<p align = "center"> <img src="/assets/amazonia.png"/> </p>
 <h3 align = "center">E-commerce platform</h1>
<p align = "center">
  <img src="https://img.shields.io/npm/v/npm?color=red&logo=npm"/>
  <img src="https://img.shields.io/node/v/jest"/>
  <img src="https://img.shields.io/github/license/kemaldemirgil/skydia?color=cyan&label=License&logo=github&logoColor=cyan"/>
  <img src="https://img.shields.io/github/issues/kemaldemirgil/skydia?color=yellow&label=Issues&logo=github&logoColor=yellow">
  <img src="https://img.shields.io/github/last-commit/kemaldemirgil/skydia?color=orange&label=Last%20Commit&logo=git&logoColor=orange">
</p>

 [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://store-amazonia.herokuapp.com/)

## 🌲 About:
Amazonia is an e-commerce application where users are able to view, add to cart and checkout certain products. The main purpose of this application was to remove the `Context API` and implement `React Redux Store` on a full-stack `MERN` application.

## 📓 Usage:
- Please select the items you desire to proceed to the checkout,
- Create and account or sign-in to continue to the payment page,
- Continue your payment on `Stripe Checkoput`

> This is just a test, nothing actually charging the account.

## 🧰 Tools & Dependencies:

### Server
```json
"dependencies": {
    "apollo-server-express": "^2.11.0",
    "bcrypt": "^4.0.1",
    "express": "^4.17.1",
    "graphql": "^15.5.0",
    "jsonwebtoken": "^8.5.1",
    "mongoose": "^5.9.7",
    "stripe": "^8.67.0"
  },
  "devDependencies": {
    "nodemon": "^2.0.2"
  }
```


### Client
```json
"dependencies": {
    "@apollo/client": "^3.3.7",
    "@stripe/stripe-js": "^1.3.1",
    "@testing-library/jest-dom": "^4.2.4",
    "@testing-library/react": "^9.5.0",
    "@testing-library/user-event": "^7.2.1",
    "graphql": "^14.6.0",
    "jwt-decode": "^2.2.0",
    "react": "^16.13.1",
    "react-dom": "^16.13.1",
    "react-redux": "^7.2.4",
    "react-router-dom": "^5.1.2",
    "react-scripts": "4.0.2",
    "redux": "^4.1.0"
  },
```

I've also used `concurrently` on the main directory to write the following scripts;
```json
"scripts": {
    "start": "cd server && npm run seed && node server.js",
    "develop": "concurrently \"cd server && npm run watch\" \"cd client && npm start\"",
    "install": "cd server && npm i && cd ../client && npm i",
    "seed": "cd server && npm run seed",
    "build": "cd client && npm run build"
  },
```

## 🌄 Images:

📃 Home Page                    | 📃 Checkout
:-------------------------:   |:-------------------------:
![](/assets/ss1.png)      |![](/assets/ss2.png)


## 📊 Notes:

> Redux is definitely great on larger size applications but, I would still consider using the `Context API` since it doesn't envolve installing another dependency. I guess it all depends on how you would like build the application. Besides that, I'm glad all the homeworks are done for the `Boot camp` now. After the final project, I would love to start working on personal projects using all these tools and possibly other languages.

<h3 align = "center">Connect with me!</h3>
<p align="center">
  <a href="https://www.linkedin.com/in/kemaldemirgil/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=plastic&logo=linkedin&logoColor=white"/></a>
  <a href="mailto: kemal.demirgil@hotmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=plastic&logo=gmail&logoColor=white"/></a>
</p>

## 📮 Issues:
If any issues or bugs are present, please submit a ticket to the `Issues` tab or contact me through kemal.demirgil@hotmail.com and I will get back to it as soon as possible.

## ©️ License:
Copyright © Kemal Demirgil. All rights reserved.
Licensed under the [MIT](https://github.com/kemaldemirgil/amazonia/blob/main/LICENSE) license.
