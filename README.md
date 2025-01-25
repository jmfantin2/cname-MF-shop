# Boilerplate for Sales Pages with Custom CNAME 🌐

This project provides a ready-to-use structure for creating highly customizable sales pages, ideal for affiliates who want to showcase their products with a simple and efficient setup. With just a few modifications to the main files, you can launch professional and attractive sales experiences.

---

## 🛠️ **What's Included?**

The project is composed of three main files:

1. **`index.html`**  
   The base structure of the page. It contains dynamic placeholders that can be easily configured in the `config.yaml` file.

2. **`style.css`**  
   The stylesheet file for customizing the page's appearance. It includes CSS variables to adjust colors, fonts, and other visual elements, allowing you to adapt the design to the product's branding.

3. **`config.yaml`**  
   A configuration file that centralizes product information, such as title, subtitle, links, images, and other page details. This file simplifies customization without the need to directly edit the HTML.

---

## 🎯 **Why Use This Boilerplate?**

This project was developed for affiliates who want to:
- Create **attractive sales pages** with a **custom CNAME**.
- **Save time** by using a ready-to-go and customizable structure.
- Easily adapt the page to a **product or campaign** with minor modifications.
- Ensure an optimized and consistent sales experience aligned with the product's branding.

---

## 🚀 **How It Works**

### 1️⃣ General Structure
The boilerplate follows a simple flow:
- The **`index.html`** renders dynamic content based on the variables configured in the **`config.yaml`** file.
- The **`style.css`** applies responsive styles, which can be customized to match the product's visual identity.
- The **`config.yaml`** centralizes key information, such as:
  - Titles and subtitles.
  - Links for the CTA button.
  - Images (logo, banner, etc.).
  - Color palette defined in the CSS.

### 2️⃣ Customization
With just a few changes to the **`config.yaml`** and **`style.css`**, you can:
- Change the page's **title**, **subtitle**, and **images**.
- Configure the **custom CNAME** to point the page to your domain.
- Adjust colors and fonts to reflect the **product's visual identity**.

### 3️⃣ Deploy and DNS
The project is recognized by **Vercel** as a Hugo framework, making deployment effortless. To configure, simply connect the repository to Vercel and deploy it. Afterward, add a **CNAME address** as a subdomain within one of the Vercel domains (e.g., `yourpage.vercel.app`) and configure it in your DNS provider, such as **Hostinger**. For example, create a CNAME record that points to the assigned Vercel domain (e.g., `yoursalespage.yourdomain.com`), and your page will be live with a custom address in no time.

---

## 🌟 **Benefits**

- **Quick Customization**: Editing just the `config.yaml` and `style.css` files is enough to launch a professional page.
- **Responsive Design**: Fully compatible with mobile and desktop devices.
- **Conversion-Focused**: Layout designed to highlight CTAs and key information.

---

## 📄 **Usage Guide**

1. **Fork and clone this repository**:
   ```bash
   git clone https://github.com/yourusername/cname-MF-shop.git
   ```
2. **Configure config.yaml**:
   Edit the values according to the product you want to promote.
   ```yaml
   title: 'Amazing Product'
   params:
     logo: 'images/my-logo.png'
     banner: 'images/my-banner.png'
     titulo: 'Discover the Secrets to Success'
     subtitulo: 'With this exclusive course, you will achieve incredible results.'
     cta_texto: 'Sign Up Now'
     cta_link: 'https://mysite.com'
   ```
3. **Customize the visual style in `style.css`**:
   Update the color variables at the top of the file.
   ```css
   :root {
     --background-from: #0c0c0c;
     --background-to: #191919;
     --text-base: #ffffff; 
     --accent-color: #c99811;
     --accent-secondary: #dfa718; 
     --link-color: #cfa01e;
     --link-hover: #e6ae14; 
     --pptos-hover: #d78a14;
     --highlight-color: #f7d860; 
     --cta-shadow: rgba(244, 197, 66, 0.4); 
     --banner-overlay: rgba(0, 0, 0, 0.5); 
   }
   ```
4. **Deploy your page**:
   - Connect your repository to Vercel and deploy it as a Hugo framework.
   - Add a CNAME in Vercel (e.g., offer.yourdomain.shop) and configure the DNS in your domain provider (e.g., Hostinger).

---

## 📝 **License**

This project is licensed under the MIT License. You are free to use and modify it.

---
