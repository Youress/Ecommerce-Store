# ComfyHouse E-commerce Website

link for deploy : https://youress.github.io/Ecommerce-Store/

This is the repository for the ComfyHouse E-commerce website, a project created with HTML, CSS, JavaScript, and utilizes Contentful for product information.

Setup
Before running the application, ensure you have the required API keys and dependencies installed.

Contentful API
To fetch product information, you need a Contentful account. Replace the space and accessToken in the client variable with your Contentful credentials:

javascript
Copy code
const client = contentful.createClient({
  space: "YOUR_CONTENTFUL_SPACE_ID",
  accessToken: "YOUR_CONTENTFUL_ACCESS_TOKEN",
});
Local Setup
Ensure you have a local development server installed. If not, you can use Live Server in Visual Studio Code or any other server of your choice.

Features
Product Display: Dynamically fetches and displays products from Contentful.
Add to Cart: Allows users to add products to their shopping cart.
Cart Functionality: Users can view their cart, adjust item quantities, and remove items.
Local Storage: Cart data is stored in local storage for persistence.
Responsive Design: Ensures a seamless experience on various devices.
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/Youress/Ecommerce-Store.git
Open the project folder in your code editor.

Replace Contentful API credentials in the app.js file.

Open index.html with a live server to view the website.

Contributions
Contributions are welcome! If you find any issues or want to enhance the project, feel free to open a pull request.

Credits
Contentful - Headless CMS for managing product data.
Font Awesome - Icons used for cart and other UI elements.
Thank you for using and contributing to ComfyHouse E-commerce!

![screencapture-youress-github-io-Ecommerce-Store-2024-01-04-17_27_25](https://github.com/Youress/Ecommerce-Store/assets/113777333/c204285b-c6ee-4aa9-a08a-bbbb177420da)
