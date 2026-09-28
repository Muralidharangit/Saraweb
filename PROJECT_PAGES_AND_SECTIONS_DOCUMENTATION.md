# Sara's Boutique — Complete Website Pages & Sections Documentation

**Project Name:** Sara's Boutique (Saraweb)  
**Brand Identity:** Luxury Indian Ethnic Wear & Handcrafted Heritage Silk Churidar Ensembles  
**Tech Stack:** Semantic HTML5, Vanilla CSS3 (Custom Luxury Design System), Bootstrap 5 Grid & Utilities, Bootstrap Icons, Swiper.js, Google Fonts (*Cormorant Garamond*, *Cinzel*, *Playfair Display*, *Poppins*, *Plus Jakarta Sans*).

---

## Table of Contents
1. [Global Components Across All Pages](#global-components-across-all-pages)
2. [Page 1: Home Page (`index.html`)](#page-1-home-page-indexhtml)
3. [Page 2: About Us / Our Story (`about.html`)](#page-2-about-us--our-story-abouthtml)
4. [Page 3: Collections / Catalog Page (`collection.html`)](#page-3-collections--catalog-page-collectionhtml)
5. [Page 4: Product Detail Page (`productdetail.html`)](#page-4-product-detail-page-productdetailhtml)
6. [Page 5: Contact Us & Flagship Boutique (`contact.html`)](#page-5-contact-us--flagship-boutique-contacthtml)
7. [Site Architecture & Section Summary Matrix](#site-architecture--section-summary-matrix)

---

## Global Components Across All Pages

All pages share a consistent luxury design language, branding elements, and shared navigational components:

### 1. Luxury Top Small Header / Announcement Bar
- **Left Column:** Boutique Support Helpline (`+91 98765 43210`) & Direct WhatsApp Concierge Chat.
- **Center Column:** Live promotional announcement (*"Complimentary Insured Shipping Across India on Orders Above ₹2,999"* with code `FESTIVE25`).
- **Right Column:** 
  - *Silk Mark Certified* trust emblem.
  - Flagship Boutique Store location indicator (*Green Park, New Delhi*).
  - Currency selector (`INR ₹`, `USD $`, `GBP £`, `EUR €`, `AED د.إ`).

### 2. Luxury Sticky Navigation Header (`<header class="luxury-header">`)
- **Brand Logo:** Elegant typographic logo ("SARA'S BOUTIQUE — Luxury Indian Ensembles").
- **Navigation Links:**
  - `Home` (`index.html`)
  - `Our Story` (`about.html`)
  - `Collections` (`collection.html`) with category dropdowns:
    - *Pure Silk Festive Sets*
    - *Anarkali Ensembles*
    - *Bridal & Reception Sets*
    - *Handloom Chanderi*
    - *Velvet Winter Suits*
  - `Why Us` (`about.html#whychoose` or `index.html#whychoose`)
  - `Testimonials` (`#testimonials`)
  - `Contact Us` (`contact.html`)
- **Action Icons & Badges:**
  - Search trigger icon (opens Search Modal).
  - Wishlist icon with dynamic counter badge.
  - Shopping Bag / Cart icon with golden count badge (`#navCartCount`) and trigger to Cart drawer / toast.
  - Mobile Hamburger Menu button.

### 3. Mobile Offcanvas Navigation Drawer (`#mobileMenu`)
- Slide-out mobile-optimized drawer with brand header, search bar, structured navigation links, currency selector, contact hotlinks, and social icons.

### 4. Interactive Search Modal (`#searchModal`)
- Modal overlay with auto-focus search input, instant keyword tags (*Anarkali*, *Banarasi Silk*, *Bridal Red*, *Chanderi*), and quick search submission.

### 5. Master Luxury Footer (`<footer class="luxury-footer">`)
- **Column 1 — Brand Story & Accreditations:** Brand narrative, Silk Mark certification badge, Handloom Mark emblem, and social links (Instagram, Facebook, Pinterest, YouTube).
- **Column 2 — Quick Links & Collections:** Direct links to Silk Churidars, Anarkali Sets, New Arrivals, Best Sellers, Lookbook, and About Us.
- **Column 3 — Customer Care & Policies:** Sizing Guide, Fabric Care Instructions, Shipping & Tracking, Return & Exchange Policy, FAQ, and Privacy Policy.
- **Column 4 — Flagship Boutique Details:** Physical address, operating hours, direct phone, WhatsApp VIP line, and concierge appointment button.
- **Bottom Footer Bar:** Copyright notice, secure payment badges (UPI, Visa, MasterCard, RuPay, American Express, NetBanking), and SSL 256-Bit encryption guarantee.

### 6. Dynamic Luxury Toast Notifications (`#luxuryToast`)
- Floating gold-accented feedback notification for cart actions, wishlist additions, newsletter subscriptions, and contact form submissions.

---

## Page 1: Home Page (`index.html`)

The flagship landing page is designed to showcase the brand's heritage, highlight new collections, drive conversions, and establish credibility.

| Section # | Section Name | Description & Key Elements |
| :--- | :--- | :--- |
| **0** | **Top Announcement Bar & Header** | Shared global top header + sticky main navigation bar with cart and search triggers. |
| **Hero** | **Hero Banner Section** (`#home`) | • High-impact editorial imagery with headline *"Timeless Elegance Woven in Pure Heritage Silk"*. <br>• Sub-headline detailing heirloom weaves and zari craftsmanship.<br>• Dual CTAs: *"Explore Collection"* & *"Watch Our Story"* (video trigger).<br>• Embedded 4-item Trust Strip (*Premium Fabrics, Perfect Fit Guarantee, Fast Pan-India Delivery, 7-Day Easy Returns*).<br>• Right-side hero slider preview controls with slide indicators. |
| **1** | **Shop by Category** (`#categories`) | • White background section with section headline and editorial intro.<br>• Circular category cards with subtle zoom and gold borders: *Anarkali Ensembles, Silk Festive Sets, Straight-Cut Suits, Velvet Winter Suits, Bridal Churidar Sets, Handloom Chanderi*. |
| **2** | **New Arrivals Swiper** (`#newarrivals`) | • Warm ivory background (`#fbf6f0`).<br>• Left sticky intro column with *"Fresh Off The Looms"* headline, subtext, and custom Swiper navigation arrow buttons.<br>• Right Swiper slider containing luxury product cards with discount badges, Silk Mark tags, price breakdowns, size chips, wishlist button, and quick-add actions. |
| **3** | **Festival Promotional Offer Banner** | • Full-width container with luxury festival banner.<br>• Highlight badge (*"Special Festive Offer — Flat 25% Off"* code `FESTIVE25`).<br>• Countdown urgency badges and 4 trust value pillars: *Handcrafted Perfection, Custom Stitching, Silk Mark Certified, Insured Shipping*. |
| **4** | **Best Sellers Swiper Showcase** | • White background section showcasing top-rated customer favorites.<br>• Filter tabs: *All Bestsellers, Pure Silk, Anarkali, Festive Wear*.<br>• Product cards with star ratings, verified review count, strike-through MRP, and interactive hover effects. |
| **5** | **Trending Occasion Collections** | • Ivory background curated visual grid.<br>• Occasion tiles with luxury typography: *Wedding & Sangeet, Festive Pooja, Daily Elegance, Reception Glamour*.<br>• Direct links to filtered catalog views. |
| **6** | **Shop by Royal Color** | • Interactive palette picker featuring signature royal colors: *Deep Ruby Maroon, Peacock Teal, Emerald Green, Mustard Ochre, Rani Rose Pink, Midnight Navy*.<br>• Instant visual color preview and filtering. |
| **7** | **Style Lookbook & Features Showcase** | • Asymmetrical editorial layout with close-up artisan shots.<br>• Feature spotlights: *Hand-Embroidery Detailing, Pure Zari Borders, Custom Sizing & Alteration Atelier*.<br>• Interactive lookbook tags. |
| **8** | **Why Choose Sara's Boutique** (`#whychoose`) | • 4-column luxury benefit grid with custom icons:<br>  1. *100% Authentic Handloom Silk*<br>  2. *Master Artisan Tailoring*<br>  3. *Silk Mark Certified Pure Fabrics*<br>  4. *Express Insured Worldwide Shipping*. |
| **9** | **Customer Reviews & Testimonials** (`#testimonials`) | • Ivory background client feedback carousel.<br>• Verified buyer reviews, 5-star ratings, bride quotes, and customer location tags. |
| **10** | **Instagram Gallery & Social Proof** | • Curated 6-image `#SarasBoutique` lifestyle grid with Instagram hover overlay, likes count, and direct link to social profile. |
| **11** | **Newsletter Subscription Banner** | • Golden bordered newsletter box with instant coupon incentive (`10% Off First Order`). |
| **Footer** | **Luxury Theme Footer** | Global comprehensive 4-column footer with policy links and payment badges. |

---

## Page 2: About Us / Our Story (`about.html`)

Dedicated brand storytelling page presenting heritage, artisan partnerships, quality standards, and leadership.

| Section # | Section Name | Description & Key Elements |
| :--- | :--- | :--- |
| **Hero** | **Story Breadcrumb Banner** | • Breadcrumb navigation (`Home / About Us`).<br>• Title: *"Our Story — Weaving Tradition into Timeless Grace"* with subtitle on preserving Indian handloom craft. |
| **1** | **Our Journey (The Beginning)** (`#journey`) | • Signature asymmetrical layout with scooped arch imagery.<br>• Narrative detailing the founding in 2012, master weaving lineage, Banarasi & Kanjivaram sourcing, and the philosophy of timeless slow fashion.<br>• Floating video play button triggering the Story Video Modal. |
| **2** | **Our Core Values** (`#our-values`) | • 4 structured value cards with golden badges:<br>  1. *Authenticity Without Compromise (100% Pure Silk)*<br>  2. *Empowering Master Weaving Communities*<br>  3. *Heirloom Quality & Sustainable Tailoring*<br>  4. *Transparent Pricing & Customer Delight*. |
| **3** | **Meet Our Team & Master Craftspeople** (`#meet-our-team`) | • Profile cards with portrait photos, designations, and artisan background: *Founders, Lead Textile Designers, Master Pattern Cutters, Head of Quality*. |
| **4** | **Mission, Vision & Impact Metrics** (`#mission`) | • Side-by-side Mission and Vision cards with decorative quotes.<br>• 4 live impact statistics:<br>  • *15,000+ Delighted Patrons*<br>  • *250+ Master Artisans Supported*<br>  • *100% Certified Silk Mark Authenticity*<br>  • *18+ Countries Shipped Worldwide*. |
| **5** | **Why Choose Sara's Boutique?** (`#whychoose`) | • In-depth breakdown of quality pillars: Yarn quality selection, custom double-seam tailoring, breathable organic cotton linings, and eco-friendly packaging. |
| **6** | **Real Stories, Real Smiles** (`#testimonials`) | • Testimonial slider featuring bridal clients, festive shoppers, and NRI customers sharing their bespoke fitting experiences. |
| **7** | **Bottom Call-to-Action (CTA)** | • Warm white banner inviting customers to explore the newest collection or book an in-boutique styling session. |
| **Modals** | **Story Video Modal & Toast** | • Pop-up high-definition video modal showcasing master weavers at work on handloom pits.<br>• Dynamic toast notification feedback. |
| **Footer** | **Luxury Theme Footer** | Master global footer with contact information and accreditation badges. |

---

## Page 3: Collections / Catalog Page (`collection.html`)

Comprehensive e-commerce catalog featuring multi-faceted filtering, sorting, responsive grid layouts, and instant quick-view modals.

| Section # | Section Name | Description & Key Elements |
| :--- | :--- | :--- |
| **Hero** | **Collection Hero Banner** | • Editorial banner with headline *"Churidar Ensembles & Festive Luxury"*.<br>• Breadcrumb trail (`Home / Collections / Churidar Sets`).<br>• Quick-filter pill chips: *All Items, Pure Silk, Anarkali, Velvet Sets, Bridal Wear, Cotton Festive*. |
| **Main** | **Main Collection Area & Sidebar** (`#mainCollectionArea`) | Split layout containing the filter sidebar and the product grid: |
| **— Filter** | **Advanced Filter Sidebar** (Desktop & Mobile Drawer) | • **Active Filters Strip:** Shows currently applied filter chips with a *"Clear All"* button.<br>• **Search Within Collection:** Real-time search keyword input.<br>• **Category Filter:** *Anarkali (12), Straight-Cut (8), Angrakha (6), Floor-Length (5), Palazzo Sets (5)*.<br>• **Fabric Type:** *Pure Mulberry Silk, Banarasi Katan, Handloom Chanderi, Raw Silk, Georgette, Velvet*.<br>• **Color Filter:** Color swatches with live tooltip preview (Maroon, Pink, Peacock Blue, Emerald Green, Mustard, Teal, Gold, Navy).<br>• **Price Range Slider:** Dual-handle interactive price slider with min/max value inputs.<br>• **Size Selector:** *XS, S, M, L, XL, XXL, Custom Sizing*.<br>• **Occasion Filter:** *Bridal, Wedding Guest, Festive Pooja, Evening Soirée, Daily Luxury*.<br>• **Availability / Discount Toggles:** *In-Stock Only, On Sale / Special Offers*. |
| **— Toolbar** | **Catalog Control Toolbar** | • Results counter (*"Showing 1–12 of 36 Ensembles"*).<br>• Layout Switcher (3-Column Grid, 4-Column Grid, List View).<br>• Sort Dropdown (*Featured, Price: Low to High, Price: High to Low, Newest Arrivals, Highest Rated*). |
| **— Grid** | **Interactive Products Grid** | • Rich product cards featuring:<br>  - Primary & secondary image swap on hover.<br>  - Silk Mark certification badge & discount ribbons.<br>  - Quick View modal button & Wishlist heart toggle.<br>  - Color swatch preview dots.<br>  - Product title, fabric description, rating stars, price with strike-through MRP.<br>  - One-click *"Add to Bag"* button with toast animation.<br>• Pagination controls with *"Previous"*, page numbers, *"Next"*, and *"Load More"* button. |
| **Banner** | **Bespoke Ensemble Promotional Strip** | • Mid-catalog luxury strip highlighting *"Made-to-Measure Custom Stitching"* with direct styling consultation trigger. |
| **Trust** | **4 Trust & Guarantees Strip** | • 4-badge assurance strip: *Silk Mark Certified, Free Pan-India Shipping, 7-Day Hassle-Free Exchange, 24/7 WhatsApp Styling Support*. |
| **Modal 1** | **Quick View Modal** (`#quickViewModal`) | • Interactive modal allowing users to inspect product images, select colors, choose sizes, adjust quantities, review detailed specs, and add to bag without leaving the catalog. |
| **Footer** | **Luxury Theme Footer** | Global 4-column luxury footer. |

---

## Page 4: Product Detail Page (`productdetail.html`)

High-conversion single product page equipped with an interactive image gallery, zoom lens, size selection, delivery pin checker, technical tabs, and related recommendations.

| Section # | Section Name | Description & Key Elements |
| :--- | :--- | :--- |
| **Hero** | **Breadcrumb & Header Banner** | • Breadcrumb trail: `Home / Collections / Pure Silk Festive / Royal Rose Pink Zari Embroidered Churidar Set`.<br>• Category badge and quick navigation back to catalog. |
| **Main 1** | **Interactive Image Gallery (Left Column)** | • **Vertical Thumbnails Carousel:** Scrollable thumbnail list with active border indicators.<br>• **Main Image Viewport:** High-resolution display with real-time mouse hover zoom lens pill.<br>• **Fullscreen Lightbox Button:** Opens image in high-resolution full-screen modal.<br>• **Wishlist Toggle Button:** Floating gold heart button.<br>• **Silk Mark Tag:** Official trust mark overlay on main view. |
| **Main 2** | **Product Details & Actions (Right Column)** | • **Product Title & Code:** Full artisanal ensemble name & SKU identifier.<br>• **Rating & Reviews Summary:** 5-star rating display with count of verified reviews.<br>• **Pricing Section:** Special discounted price, strike-through original MRP, saved percentage badge, and tax inclusion note.<br>• **Stock Urgency Alert:** *"Hurry! Only 3 left in stock at our New Delhi Boutique"* badge.<br>• **Color Selector:** Interactive swatches with active selection label (*Royal Pink, Peacock Blue, Emerald Green, Maroon*).<br>• **Size Selector & Size Guide:** Size pills (*XS, S, M, L, XL, XXL, Custom Made-to-Measure*) + link to open the Size Guide Modal.<br>• **Quantity Stepper:** Responsive `-` / `+` counter.<br>• **Call-to-Action Buttons:**<br>  - Primary *"Add to Shopping Bag"* button with gold sheen effect.<br>  - Secondary *"Buy It Now"* direct checkout button.<br>  - Direct *"Enquire via WhatsApp Concierge"* button.<br>• **Pincode Delivery Estimator:** Input field with instant check for dispatch date and Cash on Delivery availability.<br>• **Key Highlights Accordion:** Fabric composition, weaving technique, inner lining, and set contents. |
| **3** | **Product Benefits 4-Feature Strip** | • 4-column golden badge strip: *100% Pure Handloom Silk, Custom Tailoring Guarantee, Express Insured Delivery, Complimentary Returns*. |
| **4** | **Product Technical Information Tabs** | • **Tab 1: Product Description:** Comprehensive artisanal narrative, silhouette details, neckline & sleeve specifications, dupatta dimensions, and styling suggestions.<br>• **Tab 2: Detailed Size & Fit Chart:** Comprehensive measurement table (Bust, Waist, Hip, Kurta Length, Pant Length, Sleeves) with how-to-measure guide.<br>• **Tab 3: Heirloom Fabric & Zari Care Guide:** Professional dry clean instructions, moisture prevention, muslin wrapping tips, and iron settings.<br>• **Tab 4: Shipping, Returns & Alterations:** Dispatch timelines, courier partners (BlueDart, DHL), return terms, and complimentary alteration policy. |
| **5** | **"You May Also Like" Related Products Carousel** | • Swiper carousel of complementary matching items, alternative colorways, and artisanal dupattas with prev/next controls. |
| **Modal 1** | **Size Guide Modal** (`#sizeGuideModal`) | • Full measurement chart popup with toggle between inches and centimeters, plus visual measuring instructions. |
| **Modal 2** | **Fullscreen Lightbox Modal** (`#lightboxModal`) | • Fullscreen overlay with image zoom, counter (`Image 1 of 5`), and next/prev navigation. |
| **Footer** | **Luxury Theme Footer** | Master global footer with customer care links. |

---

## Page 5: Contact Us & Flagship Boutique (`contact.html`)

Customer support, bespoke appointment booking, interactive FAQ, and flagship boutique locator.

| Section # | Section Name | Description & Key Elements |
| :--- | :--- | :--- |
| **Hero** | **Contact Hero Banner** | • Breadcrumb trail (`Home / Contact Us`).<br>• Headline: *"Connect with Sara's Boutique — We are Delighted to Assist You"*, emphasizing bespoke bridal orders and styling consultations. |
| **Main** | **Contact Information & Inquiry Section** | 2-column split layout: |
| **— Info** | **Boutique Information Card (Left Column)** | • **Flagship Store Address:** *Plot No. 42, Main Market, Green Park, New Delhi - 110016* with nearby landmark details.<br>• **Direct Helpline & WhatsApp Concierge:** Direct call and chat clickables.<br>• **Email Addresses:** Customer care, bespoke orders, and press inquiries.<br>• **Boutique Hours:** Mon–Sat (10:00 AM – 8:00 PM), Sun (11:00 AM – 6:00 PM).<br>• **Social Connects:** Links to Instagram, Facebook, Pinterest, and YouTube. |
| **— Form** | **Interactive Inquiry & Appointment Form (Right Column)** | • Name, Email, Phone Number inputs.<br>• **Inquiry Subject Dropdown:** *Bespoke Bridal Appointment, Custom Sizing & Alterations, Order Tracking, Wholesale/Collaborations, General Inquiry*.<br>• **Preferred Contact Method:** *WhatsApp, Email, Phone Call*.<br>• Message textarea with live character counter.<br>• *"Submit Inquiry / Book Appointment"* button with instant validation and luxury toast feedback. |
| **Store** | **Store Location & Visit Guide** | • Flagship store imagery with location details.<br>• Valet parking information, nearest metro station guide (*Green Park Metro Station - Yellow Line*), and map directions link. |
| **Trust** | **Service Guarantees Strip** | • 4 assurance badges: *Private Bridal Lounge, In-House Master Tailors, Insured Worldwide Shipping, 24/7 WhatsApp Assistance*. |
| **FAQ** | **Frequently Asked Questions Accordion** (`#faqs`) | • Luxury accordion answering key questions:<br>  1. *How do I order custom sizing / made-to-measure?*<br>  2. *What are the shipping timelines across India and internationally?*<br>  3. *Are all fabrics Silk Mark certified?*<br>  4. *What is your exchange and return policy?*<br>  5. *Can I book a private bridal consultation at the Delhi boutique?* |
| **Banner** | **Newsletter Subscription Banner** | • Golden subscription box with instant discount voucher. |
| **Footer** | **Luxury Theme Footer** | Master global footer. |

---

## Site Architecture & Section Summary Matrix

| Page File | Page Title | Total Main Sections | Key Interactive Features |
| :--- | :--- | :---: | :--- |
| [index.html](file:///e:/Projects/Saraweb/Saraweb/index.html) | Home Page | 12 Sections | Hero Slider, Category Cards, Swiper Carousels, Royal Color Picker, Lookbook, Instagram Feed, Toast |
| [about.html](file:///e:/Projects/Saraweb/Saraweb/about.html) | Our Story / About Us | 7 Sections | Scooped Arch Layout, Video Modal, Value Cards, Team Profiles, Impact Metrics, Testimonials |
| [collection.html](file:///e:/Projects/Saraweb/Saraweb/collection.html) | Collections / Catalog | 5 Sections + Filter Sidebar | Multi-Faceted Filters (Price, Fabric, Color, Size, Category), Quick View Modal, Grid Switcher, Pagination |
| [productdetail.html](file:///e:/Projects/Saraweb/Saraweb/productdetail.html) | Product Details | 5 Sections + 2 Modals | Zoom Lens Gallery, Fullscreen Lightbox, Color/Size Pickers, Pincode Checker, Technical Tabs, Size Guide |
| [contact.html](file:///e:/Projects/Saraweb/Saraweb/contact.html) | Contact Us & Boutique | 6 Sections | Inquiry & Appointment Form, Flagship Location Guide, FAQ Accordion, WhatsApp Concierge, Newsletter |

---

## Summary of Design Tokens & Theme Assets

- **Primary Colors:** Royal Gold (`#c5a059`), Deep Navy/Black (`#111827`, `#0c0f14`), Warm Ivory (`#fbf6f0`, `#f7efe5`), Rich Maroon (`#800020`), Peackock Teal (`#005f73`).
- **Typography:** 
  - Headings: *Cormorant Garamond* & *Playfair Display*
  - Subtitles & Badges: *Cinzel*
  - Body & UI: *Poppins* & *Plus Jakarta Sans*
- **Interactive Modals:** Search Modal, Size Guide Modal, Quick View Modal, Lightbox Zoom Modal, Story Video Modal.
- **Interactive JavaScript Modules:** Swiper.js carousels, live filter and search engine, quantity counters, pincode delivery checkers, interactive image zoom lens, and dynamic cart/wishlist toast feedback.
