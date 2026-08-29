# 🛍️  Ecomexperts Hiring Test - Theme Customization

**Developer:** Ahmad Hassan  
**Live Store Preview:** [Click here to view the live store](https://bo5zkb0p97t0wpqc-100659200311.shopifypreview.com)

## 📌 Project Overview
This repository contains my submission for the Ecomexperts Shopify Developer Hiring Test. The objective was to translate a provided Figma design into a pixel-perfect, fully functional Shopify page built completely from scratch, without relying on pre-existing Dawn theme sections. 

## 🚀 Key Features & Requirements Met

* **Custom Sections Built from Scratch:** 
  * Developed `custom-banner.liquid` and `custom-product-grid.liquid` entirely from scratch.
  * Ensured zero reliance on default Dawn theme components.
* **Shopify Theme Customizer Integration:** 
  * Configured robust JSON schemas allowing merchants to easily edit banner text, subtitle, description, and button links.
  * Implemented customizable product blocks (up to 6) for the product grid.
* **Vanilla JavaScript Quick View Modal:** 
  * Built a dynamic Quick View popup using **strict Vanilla JavaScript (No jQuery)**.
  * Leveraged JSON data embedded in the Liquid loop to dynamically render product titles, prices, descriptions, images, and variant options inside the modal.
* **Advanced AJAX Cart Logic:** 
  * Implemented conditional cart logic via Shopify's `/cart/add.js` API. 
  * **Special Rule Executed:** When a user adds any product with the specific variant combination of **"Black"** and **"Medium"**, the script automatically detects this and adds the "Soft Winter Jacket" to the cart alongside it in a single batch request.
* **Pixel-Perfect & Responsive:** 
  * Styled with custom CSS to match the provided Figma prototype exactly.
  * Fully responsive design that adapts cleanly for mobile viewports, including stacking grid columns and scaling typography.

## 🛠️ Tech Stack
* Shopify Liquid
* Vanilla JavaScript (ES6+)
* HTML5 & CSS3
* Shopify AJAX Cart API

## ⏱️ Note on Time Tracking (Time Doctor)
*Please note: I inadvertently missed starting the Time Doctor tracker at the absolute beginning of the repository setup, but the core development, JavaScript logic implementation, layout styling, and final QA/testing were fully tracked. Thank you for your understanding!*

---
*Thank you for reviewing my application and code!*
