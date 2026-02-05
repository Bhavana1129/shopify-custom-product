# 🛍️ Shopify Custom Product Metafields

This project showcases a **Shopify theme customization** that displays additional, product-specific details such as **Manufacturer**, **Material**, and **Care Instructions** on the product page using **Shopify product metafields**.

It demonstrates a scalable and admin-friendly approach to extending Shopify’s default product data without hardcoding values.

---

## ✨ Features
- Custom **product metafields** for additional details
- Dynamic rendering using **Shopify Liquid**
- Conditional display (shows data only when available)
- Clean and responsive UI section on product page
- Easy to manage from Shopify Admin

---

## 🧰 Technologies Used
- Shopify Liquid  
- HTML5  
- CSS3  
- JavaScript  
- Shopify Admin (Metafields)

---

## 🛠️ How It Works
1. Custom metafields are created for products in the Shopify Admin.
2. Each product can have unique values for manufacturer, material, and care instructions.
3. Liquid templates fetch and display these values dynamically on the product page.
4. Conditional checks ensure a clean UI with no empty fields.

---

## 🚀 How to Use
1. Create a **Shopify Development Store**
2. Add product metafields:
   - `custom.manufacturer` (Single line text)
   - `custom.material` (Single line text)
   - `custom.care_instructions` (Multi-line text)
3. Upload the theme files from this repository into your Shopify theme
4. Assign metafield values to products
5. View the output on the product page

---

## 🖼️ Screenshots

### Product Page Output
![Product Page with Custom Metafields](screenshots/product-page.png)

### Product Metafields in Admin
![Product Metafields Admin](screenshots/metafields-admin.png)

> 📌 *Screenshots are taken from a Shopify Development Store.*

---


## 📌 Use Case
Ideal for stores that need to display extra product information not supported by Shopify’s default fields, while keeping data flexible and manageable for non-technical users.

---

## 👩‍💻 Author
**Bhavana V**  
Full Stack / Shopify Frontend Developer

---

⭐ *Project tested on a Shopify Development Store*
