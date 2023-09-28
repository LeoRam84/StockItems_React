# Project README

## Inventory/StockItems Management SPA

A more complex React project, this is a Single Page Application (SPA) for stock items management, built with React, React Router, Vite, CSS and Node.js. It allows you to manage your inventory, add new items, delete items, update existing items, and view various inventory statistics. Execute the 'npm run dev' command in your terminal within the project directory, after installing Node.js, npm and Vite. 

## Features

  Dashboard displaying:
  - Total quantity of different items
  - Total quantity of items
  - Quantity of items added in the last 10 days
  - List of items added in the last 10 days
  - Quantity of items with less than 10 in stock
  - List of items with less than 10 in stock

  Inventory list page with:
  - Table displaying summarized item information
  - Buttons for viewing more details, updating, and deleting items

  Detailed item information page with:
  - All item properties
  - Buttons for updating and deleting the item

  Create new item page with fields for:
  - Name
  - Quantity
  - Price
  - Category
  - Description

- Update item page with the same format as the new item creation page.

- Client-side navigation for a seamless user experience.

- Data persistence using local storage to preserve data between sessions.

## Getting Started

Follow these steps to get the project up and running on your local machine:

1. Install Node.js, npm and Vite.

2. Clone the repository:

   ```bash
   git clone https://github.com/LeoRam84/StockItems_React
   cd StockItems_React

3. Execute the 'npm run dev' command in your terminal within the project directory, after installing Node.js, npm and Vite.


------------------------------------------------------------------------------------------------------------------

## Node.js and npm

https://nodejs.org/en/download

https://docs.npmjs.com/downloading-and-installing-node-js-and-npm

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh