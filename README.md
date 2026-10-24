# CampusStay-SL_DCOMP204_Assignment-2
markdown# CampusStay SL - Student Accommodation Platform
## DCOMP 204: Web Design - Assignment 2

**LIMKOKWING UNIVERSITY OF CREATIVE TECHNOLOGY - SIERRA LEONE**
**Faculty of Information & Communication Technology**

---

### STUDENT INFORMATION
- **Full Name:** [Benjamin Sam Bangura]
- **Student ID:** [905005828]
- **Programme:** Diploma in Information and communication Technology
- **Module:** DCOMP 204 - Web Design
- **Assignment:** Assignment 2 - Multi-Page Responsive Website
- **Lecturer:** Mr. Amadu Kamara
- **Submission Date:** October 2026

### GITHUB LINKS
- **Repository:** https://github.com/benjaminsam030-coder/CampusStay-SL-DCOMP204-Assignment2
- **Live Site (GitHub Pages):** https://benjaminsam030-coder.github.io/CampusStay-SL-DCOMP204-Assignment2/
- **Collaborator Added:** amadu.kamara@limkokwing.edu.sl

---

### 1. PROJECT OVERVIEW
CampusStay SL is a responsive multi-page website designed to help students in Freetown, Sierra Leone find safe, affordable accommodation near their university campuses. The platform addresses the real problem faced by students like Fatmata Sesay who struggle to find verified housing near Hill Station.

The website contains 5 fully interconnected pages built with HTML5 and CSS3, and is fully responsive on Mobile, Tablet, and Desktop.

### 2. SITEMAP
The website follows a hierarchical structure as shown in the A3 design board:
CampusStay SL (Home)
                               |
   |           |              |           |           |
 Home      Listings       Details       About      Contact
   index.html listings.html details.html about.html contact.html--> All 6 listings --> Details Page--> Popular Areas --> Listings--> Recent Listings --> Detailsjavascript
**Navigation Logic:**
- Logo `CampusStay SL` on ALL pages leads to Home Page (index.html)
- All property cards (Image, Title, View Details Button) lead to Details Page (details.html)
- No broken links - 100% connected navigation

### 3. DESCRIPTION OF 5 PAGES

#### Page 1: Home - index.html
- **Purpose:** Landing page for first-time visitors
- **Content:** Hero section with search box (Location, Room Type, Price), Popular Areas near Campus (Hill Station, Jui, Congo Cross), Recent Listings (3 properties)
- **Links:** All Popular Areas link to listings.html, All Recent Listings link to details.html

#### Page 2: Listings - listings.html
- **Purpose:** Browse all available student accommodation
- **Content:** Left sidebar with filters (Price Range NLe 1000-5000, Facilities: WiFi, Water, Electricity, Room Type: Single, Self-Contain, Shared), Right side with 6 property cards in grid layout, Map view with Price Box, Pagination
- **Major Requirement Met:** Every listing is clickable and leads to details.html

#### Page 3: Details - details.html (MAJOR FEATURE - 30 MARKS)
- **Purpose:** Show full information about a single property
- **Content:** 
    - Large property image
    - Property ID: CSL-10234, Availability, Property Type
    - Facilities Section: WiFi, Laundry, Kitchen, Water 24/7, Security CCTV
    - Security & Campus Proximity: 1.2km distance, NLe 10 transport, 4.8/5 safety rating, Bus stop location
    - Student Reviews: 4.8/5 (12 reviews)
    - Google Map integration (Hill Station, Freetown)
    - Right sidebar: Price Box (NLe 3000/month + Service fee + Deposit), Landlord info (Mr. Kamara), Contact buttons (Contact Landlord, WhatsApp: +232 77 123 456, Call), Similar Properties (3 properties all linked to details.html)

#### Page 4: About - about.html
- **Purpose:** Company background and credibility
- **Content:** Mission statement, Our Story (Founded 2023 at Limkokwing, from 10 to 500+ listings), Team section (John Doe - Founder, Fatima Kamara - Designer, Aminata Sesay - Marketing), Statistics (500+ Properties, 2000+ Students Helped, 4 Cities, 98% Satisfaction), Footer links: Privacy Policy, Terms, Careers, Help Center

#### Page 5: Contact - contact.html
- **Purpose:** User support and property listing for landlords
- **Content:** Left: Contact Form (Name, Email, Phone, Message), Landlord Section - List Your Property Form (Title, Room Type, Location, Description, Photo Upload max 6, Price, Facilities checkboxes), Right: Google Map, Address: Hill Station Freetown, Phone, Email, Working Hours

### 4. KEY FEATURES IMPLEMENTED

**A. Navigation Requirements (As per brief):**
1.  Logo as Home Button: On all 5 pages, `<a href="index.html" class="logo">CampusStay SL</a>` - Clicking logo always returns to home
2.  Interconnected Listings: In index.html (3 recent listings) and listings.html (6 listings), every image, title, and View Details button has `href="details.html"`

**B. Responsive Design (25 Marks):**
Implemented using CSS Media Queries:
- **Mobile (<768px):** 1 column grid, navbar stacks vertically, search box stacks vertically, hamburger-friendly layout. Tested on iPhone SE (375px)
- **Tablet (768px - 1024px):** 2 column grid, filters stack above listings, details layout stacks. Tested on iPad Air (768px)
- **Desktop (>1024px):** 3 column grid, side-by-side layout (filters + listings, details + price box), full horizontal navbar. Tested on 1440px

**C. Other Features:**
- External CSS file (style.css)
- 12+ images from Unsplash
- Hover effects on cards (transform: translateY)
- Sticky navbar
- Consistent color scheme (Primary Blue #2563eb)

### 5. TECHNOLOGIES USED
- **HTML5:** Semantic structure for 5 pages
- **CSS3:** Flexbox, Grid, Media Queries, Transitions, Shadows
- **Tools:** VS Code, Chrome DevTools / Firefox Responsive Mode, GitHub, Figma (for wireframes in Assignment 1)

### 6. HOW TO RUN THE WEBSITE
**Method 1 - Local:**
1. Download repository as ZIP
2. Extract to Desktop as `CampusStay_SL_Website`
3. Double-click `index.html` - opens in default browser
4. Test navigation: Click Logo -> Home, Click any property -> Details, Navigate through all pages

**Method 2 - VS Code:**
1. Open folder in VS Code
2. Install extension "Live Server"
3. Right-click index.html -> Open with Live Server
4. Site runs at localhost:5500

**Method 3 - GitHub Pages (Live Online):**
1. GitHub repo -> Settings -> Pages -> Source: main branch -> Save
2. Live link will be: https://YOUR_USERNAME.github.io/CampusStay-SL-DCOMP204-Assignment2/

### 7. FOLDER STRUCTURECampusStay-SL-DCOMP204-Assignment2/
│
├── index.html          (Home Page)
├── listings.html       (Listings Page - 6 properties linked to details)
├── details.html        (Details Page - Major Feature)
├── about.html          (About Page)
├── contact.html        (Contact Page)
├── style.css           (All styling + Responsive)
├── README.md           (This file)
│
└── screenshots/        (Responsive Test - 10 marks)
    ├── mobile_home.png      (iPhone SE 375px)
    ├── tablet_home.png      (iPad 768px)
    ├── desktop_home.png     (Desktop 1440px)
    └── mobile_listings.png  (Listings on Mobile)javascript
### 8. RESPONSIVE TESTING - SCREENSHOTS
Screenshots taken using Firefox: Ctrl+Shift+M -> Select Device -> Right-click -> Take Screenshot -> Save full page

| Screenshot File | Device | Page | Resolution |
| :--- | :--- | :--- | :--- |
| mobile_home.png | iPhone SE | Home | 375 x 667 |
| tablet_home.png | iPad Air | Home | 768 x 1024 |
| desktop_home.png | Desktop | Home | 1920 x 1080 |
| mobile_listings.png | iPhone SE | Listings | 375 x 667 |

All screenshots are included in the `/screenshots` folder and printed in the hardcopy Word document.

### 9. USER PERSONA AND JOURNEY

**User Persona:**
Name: Fatmata Sesay, Age: 21, Programme: 2nd Year ICT, University: Limkokwing University, Budget: NLe 3000/month, Needs: Self-Contain near Hill Station, Safe area for female student, WiFi for online classes and assignments, Water 24/7, Pain Points: Scams, far distance, no water, unsafe areas.

**User Journey Map:**
1.  Enters Home Page -> Sees Hero "Find Your Perfect Student Home"
2.  Types "Hill Station" in search -> Selects "Self-Contain" -> Clicks Search -> Goes to Listings
3.  On Listings -> Filters: Price NLe 1000-5000, Facility: WiFi -> Sees "Self-Contain Hill Station - NLe 3000"
4.  Clicks View Details -> Goes to Details Page -> Checks Facilities (WiFi Yes, Water Yes), Checks Security & Proximity (1.2km, 5 min walk, Safety 4.8/5, Transport NLe 10), Reads Reviews (12 reviews, 4.8 stars)
5.  Checks Price Box (NLe 3000 + NLe 200 service + NLe 1000 deposit) -> Sees Landlord Mr. Kamara responds in 1 hour
6.  Clicks WhatsApp button -> Contacts Landlord -> Schedules visit

### 10. HARDCOPY SUBMISSION CHECKLIST
- Cover Page with Name, ID, Module, Lecturer
- This README printed
- Sitemap diagram (black & white)
- 4 Screenshots (Mobile, Tablet, Desktop)
- Wireframes from Assignment 1
- Code printout (5 HTML + 1 CSS) in Tahoma Size 10
- GitHub link: https://github.com/YOUR_USERNAME/CampusStay-SL-DCOMP204-Assignment2
- A3 Design Board

### 11. REFERENCES
- Images: https://unsplash.com (Free student housing images)
- Design Inspiration: Airbnb, Jumia House Sierra Leone
- W3Schools for HTML/CSS reference

---

**DECLARATION:** This work is my own original work. All code is written by me for DCOMP 204 Assignment 2. Images are from Unsplash free license.

**END OF README**
© 2026 CampusStay SL - Limkokwing University - DCOMP 204
