🛒 Mini Project – Product Store Web Application
📌 Project Overview

This mini project is a Product Store web application developed using HTML, CSS, and JavaScript.
It fetches product data from an external API and provides features like product listing, search, pagination, product details, and search history, all working on GitHub Pages (static hosting).

🚀 Features

📦 Display products dynamically using API

🔢 Client-side pagination on home page

🔍 Product search functionality

💡 Search suggestions using localStorage

🧾 Search history with timestamp

🛍️ Product detail page

🗑️ Clear search history option

🌐 Fully compatible with GitHub Pages

🧑‍💻 Technologies Used

HTML – Structure of web pages

CSS – Styling and layout

JavaScript – Dynamic behavior and logic

DummyJSON API – Product data source

LocalStorage – Storing search and view history

mini-project/
│
├── index.html        # Home page with product list & pagination
├── style.css         # Common styling
├── script.js         # Product fetch, pagination, search logic
│
├── product.html      # Product detail page
├── product.css       # Styling for product page
├── product.js        # Product detail logic
│
├── search.html       # Search results page
├── search.js         # Search filtering logic
│
├── history.html      # Search history page
├── history.js        # History handling logic
|__ history.css       # Styling for histoy page
│
└── README.md         # Project documentation


🔗 API Used

Products API:

https://dummyjson.com/products


Single Product API:

https://dummyjson.com/products/{id}

⚙️ How It Works

Products are fetched from the API on the home page.

Pagination displays limited products per page.

Clicking a product opens the product detail page.

Search queries are saved in localStorage.

Search history is displayed with date & time.

Users can clear search history anytime.

🌐 Deployment

This project can be hosted on GitHub Pages without any backend.

👨‍🎓 Developed By

Mitali Manaktala
B.Tech (AI & ML) – Mini Project