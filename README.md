# ShopSmartly

ShopSmartly is a full-stack web application designed to help users find products at the best prices among different online retailers. 
This project utilizes Python, Django, Selenium, web scraping, and connects to an online database using PostgreSQL via the Psycopg2 connector.

## Features

- **Price Comparison:** Search for products and compare prices across various online retailers.
- **User Accounts:** Create accounts, save preferences, and track your search history.
- **Web Scraping:** Utilizes Selenium for web scraping to fetch real-time pricing information.
- **Online Database:** Connects to a PostgreSQL database hosted on Railway for data storage.

## Tech Stack

- **Frontend:**
  - HTML, CSS, JavaScript
  - Django Templates for dynamic content rendering
  
- **Backend:**
  - Python
  - Django Framework
  - Selenium for web scraping
  
- **Database:**
  - PostgreSQL hosted on Railway
  - Psycopg2 for database connection

## Usage

 - **Search for Products:**
   - Go to the search box located at the top of the page.
   - Type the desired product and press Enter or click on the magnifying glass icon.
 
 - **View Search Results:** 
   - The result page will display a list of products organized by site.
   - Each product entry includes the product image, name, price, site, and the quotation date.

  - **Navigate to External Sites:**
    - To view more details or make a purchase, click on the site link associated with each product.
      
  - **Navigation:**  
    - Return to the main page by clicking on the Shop Smartly! navbar name or icon.
  
  - **Upcoming Upgrades:**
    - Future upgrades will include the ability to search by category, allowing for more refined searches.
    - Save your favorite products to keep track of price updates and easily find them later.
    - Register an account to receive notifications for selected items, ensuring you stay informed about any price changes.
