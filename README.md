## Project Overview
This project automates navigating, searching, filtering, counting, and validating products on Daraz.pk using **Selenium** with Python, following the **Page Object Model (POM)** structure.

## Implemented Features
1. Setup project with Selenium and required drivers.  
2. Navigate to Daraz.pk homepage.  
3. Search for "electronics" using the search functionality.  
4. Apply brand filter to narrow down results.  
5. Attempt to apply price filter (500–5000).  
6. Count products in search results and validate that the count is greater than 0.  
7. Open product details for the first product in the results.  
8. Verify if free shipping is available for the product. 

## How to Run
1. Download and extract the zip folder from this repository.  
2. Ensure Python 3.x and Selenium are installed.  
3. Verify that the included ChromeDriver matches your Chrome version. If it does not, replace it with a compatible version.  
4. Run the test script to execute the automation.

## Issue the Project is facing:
The price filter 'Apply' button could not be automated. I made umpteen attempts, but it could not be triggered.
