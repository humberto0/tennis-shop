# Tennis Shop - React Application

Tennis Shop is a simple e-commerce application built using React that allows users to add products to their shopping cart, adjust the quantity of products in the cart, and complete the purchase process. The application uses a JSON server as a mock API to simulate server-side functionality.

### Dashboard

![Captura de tela de 2023-04-04 12-26-20](https://user-images.githubusercontent.com/15384670/229848342-6643fc64-dd5b-484d-acc7-c99458773c4e.png)

###Cart

![Captura de tela de 2023-04-04 12-26-28](https://user-images.githubusercontent.com/15384670/229848421-46cedb59-d0f4-4455-9233-af1c1532ec80.png)



## Dependencies

The following packages are used in this project:

* @testing-library/jest-dom: Testing utility library for Jest
* @testing-library/react: Testing utility library for React
* @testing-library/user-event: Testing utility library for user events
* @types/jest: Type definitions for Jest
* @types/node: Type definitions for Node.js
* @types/react: Type definitions for React
* @types/react-dom: Type definitions for React DOM
* axios: Promise-based HTTP client for the browser and Node.js
* polished: A lightweight toolset for writing styles in JavaScript
* react: A JavaScript library for building user interfaces
* react-dom: React package for working with the DOM
* react-icons: A library of icons for React
* react-router-dom: DOM bindings for React Router
* react-scripts: Configuration and scripts for Create React App
* react-toastify: A toast notification library for React
* styled-components: A CSS-in-JS library for React
* typescript: A typed superset of JavaScript
* web-vitals: Library for measuring web performance metrics

## Getting Started

- To get started with the application, first clone this repository to your local machine using the command:

```bash
git clone https://github.com/your-username/tennis-shop.git
```

- Then, navigate to the project directory and install the dependencies by running:

```bash
yarn
```

- After that, start the JSON server using the command:

```bash
 yarn json-server --watch server.json --port 3333
```
* This will start the JSON server on port 3333 and load the data from the server.json file. The data consists of an array of tennis products with their names, prices, and images.

- To start the application, run the following command:

```bash
 yarn start
```

## Usage



The Tennis Shop application consists of the following pages:

* Home: This is the landing page of the application where users can see the list of available tennis products. Users can add products to their cart from this page.
* Cart: This page displays the products that the user has added to their cart. Users can increase or decrease the quantity of products, remove products from the cart, and checkout from this page.
* Checkout: This page displays a summary of the user's order and allows them to enter their shipping and payment information.

To use the application, start by navigating to the Home page. Here, you can see the list of available tennis products. To add a product to your cart, click on the "Add to Cart" button below the product. You can then navigate to the Cart page by clicking on the cart icon in the header.

On the Cart page, you can see the products that you have added to your cart. To increase or decrease the quantity of a product, use the "+" and "-" buttons next to the product. To remove a product from the cart, click on the "Remove" button below the product. When you are ready to checkout, click on the "Checkout" button.

On the Checkout page, enter your shipping and payment information and click on the "Place Order" button to complete your purchase.

## Folder structure

```bash
├── public
│   ├── index.html
│   ├── favicon.ico
│   └── manifest.json
├── src
│   ├── assets
│   ├── components
│   ├── pages
│   ├── services
│   ├── styles
│   ├── utils
│   ├── App.tsx
│   ├── index.tsx
│   ├── react-app-env.d.ts
│   └── setupTests.ts
├── server.json
├── package.json
├── package-lock.json
├── README.md
├── tsconfig.json
└── yarn.lock

```

## Acknowledgments

This application was built as a project for learning React and JSON server. Special thanks to [Your Name Here] for providing the original project idea and design.

## License

This project is licensed under the MIT License - see the LICENSE file for details.




