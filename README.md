# How to Fetch API Data with Axios and React Beginner to Advance

## Create a new React component file in your text editor. You can name it whatever you like, but for the sake of this example, let's call it ProductList.js.

## Install Axios by running the following command in your terminal:

- npm install axios

## Create a component folder and ProductList.js file:

- Import Axios into your ProductList.js file:
- import axios from 'axios';

## Create a functional component called ProductList. Inside the component, use the useState hook to create a state variable called products and set its initial value to an empty array:

- import React, { useState } from 'react';
  import axios from 'axios';

function ProductList() {
const [products, setProducts] = useState([]);

// ...
}

## Use the useEffect hook to fetch the data from the Fake Store API when the component mounts

## In the return statement, map over the products array and display the product information. For example, you can display the product name, price, and image

## Finally, export the ProductList component at the bottom of the file

## import the ProductList file into App.js
