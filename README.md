# Coconut Bird's Nest Website

## Project Overview
This repository contains the source code for the official website of **Coconut Bird's Nest**, a premium bird's nest product business. The website provides information about products, packaging, business background, and an interactive gallery. It is fully responsive and optimized for desktop and mobile devices, with a focus on usability, accessibility, and secure delivery.

The site is deployed via **GitHub Pages** with a **custom domain** (`coconutbirdsnest.com`) and served over **HTTPS** using Let’s Encrypt. Domain registration and DNS management are handled through **Hostinger**.

---

## Live Website
The website is publicly accessible at:  
[https://coconutbirdsnest.com](https://coconutbirdsnest.com)

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/c5003958-8703-40c1-ba96-d02adc2e30ad" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/e12d4a9d-0708-45ec-8667-4f6956b7c66b" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/aa00a742-d773-4417-b976-250ffc1c274e" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/eff34a33-1975-43f3-bee4-874b0d0155b4" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/ce7892da-99d7-4f0a-b567-7080028bf39b" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/ba8ac828-4c4c-48ef-89b1-9894b4d115b6" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/17b74b9b-739f-4145-ab32-3cd14cb265c3" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/a88f16ff-6af1-4996-9c0e-fc06b8ff4438" />

---

## Features

- **Header**: Contains the business logo and navigation menu for easy access to different pages.  
- **Hero Section**: Main banner area with a heading, description, hero image, and a **call-to-action button** linking to the products page.  
- **Interactive Gallery**: Lightbox-enabled gallery for viewing product images.  
- **Collapsible Navigation Menu**: Improves usability on smaller screens (powered by custom JavaScript).  
- **Footer**: Contains contact information, social media links, and business location.  
- **HTTPS Secure**: All traffic is served over HTTPS with automatic certificate renewal.  

---

## Technology Stack

- **HTML5 & CSS3** – Structure and styling for the website.  
- **JavaScript** – Custom code for collapsible menu and interactive Lightbox gallery.  
- **Google Fonts** – Typography (Poppins).  
- **Font Awesome 4.7.0** – Icons for navigation and social media links.  
- **Lightbox.js** – Interactive gallery modal functionality.  
- **GitHub Pages** – Hosting and continuous deployment.  
- **Hostinger** – Domain registration, DNS management, and initial domain configuration.

---

## Repository Structure

The repository contains the main HTML files: `index.html`, `products.html`, `about.html`, and `contact.html`. The `style.css` file contains all custom styling, and `lightbox.min.css` and `lightbox-plus-jquery.min.js` support the interactive gallery.  

The `walet` folder contains all image assets used on the website, including logos (`goldenlogo.png` and `whitelogo.png`), banner images (`5.jpg`, `6.jpg`, `0.png`), and gallery images. All HTML pages reference these assets using relative paths to ensure proper deployment via GitHub Pages.

**Folder hierarchy summary:**

- `walet/` → images for logos, banners, and gallery  
- `index.html` → homepage  
- `products.html` → products page  
- `about.html` → business info  
- `contact.html` → contact information  
- `style.css` → main stylesheet  
- `lightbox.min.css` → lightbox gallery styles  
- `lightbox-plus-jquery.min.js` → lightbox gallery functionality  

---

## Deployment

- **GitHub Pages**: The website is built and deployed automatically from the `main` branch.  
- **Custom Domain**: Configured using a `CNAME` file pointing to `coconutbirdsnest.com`.  
- **SSL/HTTPS**: GitHub Pages automatically provisions and renews the SSL certificate via Let’s Encrypt.  
- **Hostinger**: Handles domain registration, DNS configuration, and initial connection to GitHub Pages.

---

## Local Development

Local development allows you to **run and test the website on your own computer** before deploying changes online. This is purely for testing purposes and does **not affect the live website** unless you have write access to the repository.

Steps:

1. Clone the repository to your computer:

```bash
git clone https://github.com/dharmawann/coconutbirdsnest-website.git
