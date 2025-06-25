1. index.php (Basic Template Code)
<?php
/*
Template Name: PrimeClick Custom Page
*/
get_header(); ?>

<div class="primeclick-hero">
    <div class="container">
        <h2>Your Ultimate Destination for Stunning, High-Quality Images</h2>
        <p>Whether you’re a designer, marketer, or content creator, PrimeClick gives you access to a growing library of beautiful, curated photos.</p>
        <ul class="features">
            <li>💎 Download premium images</li>
            <li>🔒 Unlock members-only content</li>
            <li>🚀 Choose your membership and start creating today</li>
        </ul>
        <p><strong>Join PrimeClick — where every click matters.</strong></p>
    </div>
</div>

<div class="primeclick-gallery">
    <h3>Here are some pictures with details which you can download from our gallery</h3>
    <div class="gallery-item">
        <img src="<?php echo get_template_directory_uri(); ?>/images/cave.jpg" alt="Cave">
        <p>
            A cave is a natural underground space, typically formed in rock, that is large enough for a person to enter. Caves are often created by the slow action of water eroding limestone or other soluble rocks over thousands of years.
        </p>
    </div>
</div>

<?php get_footer(); ?>

 2. style.css (Custom Styling)
.primeclick-hero {
    background: #fff;
    padding: 40px;
    text-align: center;
    color: #b63b2f;
}

.primeclick-hero h2 {
    font-size: 28px;
    margin-bottom: 10px;
}

.primeclick-hero ul.features {
    list-style-type: none;
    padding: 0;
    margin: 20px 0;
}

.primeclick-hero ul.features li {
    font-weight: bold;
    margin-bottom: 8px;
}

.primeclick-gallery {
    padding: 30px;
    background: #fafafa;
    color: #b63b2f;
}

.gallery-item {
    display: flex;
    align-items: flex-start;
    gap: 20px;
    margin-top: 20px;
}

.gallery-item img {
    max-width: 400px;
    height: auto;
    border-radius: 8px;
}





# PrimeClick–A Photogrphic Website

## 🔍 Project Overview
**PrimeClick** is a photography-based website where users can view images and download them by purchasing a membership. The website is fully built using WordPress.

---

## ✅ My Contributions

I independently developed the entire website as part of my internship project. Below are the key areas of my contribution:

### 🔧 Features Implemented:
- Built the complete website using WordPress
- Designed and customized the entire layout and theme
- Created essential pages:
  - Home
  - Gallery
  - Register
  - Login
  - Account/Profile
- Installed and configured the **Restrict Content Pro** plugin
- Created membership levels (e.g., Free, Premium)
- Restricted image downloads for non-members
- Ensured full responsive design for mobile and desktop

---

## 🔗 Live Site (if available)
primclick.xyz 

---

## 💻 Technologies Used
- WordPress CMS  
- Elementor Page Builder  
- Restrict Content Pro Plugin  
---




---

## 🙋 Developer Info
**Name:** Indronil Dey Niloy 
**Project for:** Independent University, Bangladesh 
**Student ID:** 2020339  

