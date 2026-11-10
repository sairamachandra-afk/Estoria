# Estoria
### Find a place to call home.

Estoria is a real estate listing website built using **HTML and CSS**. It provides a clean, modern interface for exploring properties for sale and rent, viewing property details, and accessing account pages.

Developed as a course project, Estoria focuses on frontend design, structured layouts, and CSS-based interactions.

## Project Details

| Project Name & Title | Team Name | Course Code | Registration Number(s) |
| --- | --- | --- | --- |
| **Estoria — Real Estate Listing Website** | **Property coders** | **K2P26AW** | 12603390, 12601442 |

## Live Website

Explore the deployed project:

**[Visit Estoria](https://sairamachandra-afk.github.io/Estoria/)**

## Video Presentation

**Video link:** To be updated.

The presentation will demonstrate the website, explain its main features, and introduce the technologies used.

## Project Overview

Estoria brings together a property discovery homepage, dedicated Buy and Rent pages, and matching sign-in and sign-up interfaces.

The project aims to:

- Organize property information in a clear, accessible layout.
- Help users browse homes by property type, budget, and bedroom count.
- Present property photographs, prices, locations, and amenities.
- Provide a consistent visual identity across different pages.
- Establish a frontend foundation for future backend integration.

**Current status:** Frontend implementation. Authentication, persistent storage, and backend services are planned.

## Features

### Home Page

- Full-screen property background.
- Estoria logo and branding.
- Centered floating navigation bar.
- Buy, Rent, and Sell navigation.
- Property search interface with location and keyword fields.

### Buy and Rent Pages

- Property cards with photographs and availability badges.
- Prices, locations, bedrooms, bathrooms, and floor-area details.
- CSS-based property type, budget, and bedroom filters.
- Reset filters and empty-result messages.
- Favourite controls with a selected visual state.
- Property-detail overlays with descriptions and amenities.
- An illustrative neighbourhood panel with clickable price markers.

### Sign-In and Sign-Up Pages

- Consistent split-screen layout and styling.
- Buyer/Owner and Agent/Builder role selection.
- Mobile-number entry for sign-in.
- Full name, email, and mobile-number fields for sign-up.
- Links between account pages and the homepage.
- Styled controls prepared for future authentication integration.

## Technologies Used

| Technology | Purpose |
| --- | --- |
| HTML5 | Page structure, navigation, and forms |
| CSS3 | Styling, transitions, and visual interactions |
| CSS Grid | Main page layouts and property grids |
| Flexbox | Navigation, form elements, and component alignment |
| CSS Selectors | Filtering, favourite states, and detail overlays |
| Google Fonts — Outfit | Website typography |
| GitHub Pages | Static website hosting |

The current frontend does not require a JavaScript framework, database, or package installation.

## Project Files

| File or Folder | Description |
| --- | --- |
| `index.html` | Main landing page |
| `Style.css` | Homepage styling |
| `Buy.html` | Properties available for purchase |
| `Rent.html` | Rental property listings |
| `listings.css` | Shared listing-page styles and interactions |
| `signin.html` | Sign-in interface |
| `signup.html` | Sign-up interface |
| `signin.css` | Shared account-page styling |
| `Logo.png` | Estoria logo and favicon |
| `background.png` | Homepage and account-panel background |
| `images/properties.png` | Property image sheet |
| `README.md` | Project documentation |

## Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/sairamachandra-afk/Estoria.git
   ```

2. Open the project folder:

   ```bash
   cd Estoria
   ```

3. Open `index.html` in your browser.

Alternatively, open the folder in **VS Code** and launch `index.html` using the **Live Server** extension.

An internet connection is needed to load Outfit from Google Fonts. A fallback sans-serif font is used if it cannot load.

## Current Functionality

| Feature | Current Behaviour |
| --- | --- |
| Page navigation | Opens the corresponding existing HTML pages |
| Listing filters | Filters the included property cards using CSS |
| Favourite controls | Changes appearance; selections are not saved to an account |
| Property details | Opens an in-page detail overlay |
| Search interface | Accepts input; keyword and location searches are not processed yet |
| Account forms | Accepts input; account creation and authentication are not connected |
| Google sign-in | Interface only; OAuth integration is pending |
| Neighbourhood panel | Illustrative layout rather than a live geographic map |

The current design primarily targets desktop screens. Some links, including Sell and Agents, point to destinations planned for later development.

## Future Development

- [ ] Sell / List Property page
- [ ] Agent directory and contact flow
- [ ] Mobile and tablet layouts
- [ ] User authentication and Google sign-in
- [ ] Database integration
- [ ] Dynamic property listings
- [ ] Working keyword and location search
- [ ] Persistent favourites
- [ ] Property enquiries and owner responses
- [ ] Live map integration

## Project Assets

The interface includes AI-generated property imagery. Property names, prices, and descriptions are sample content used to demonstrate the design.

## Team Members

| Member | Registration Number |
| --- | --- |
| Member 1 | 12603390 |
| Member 2 | 12601442 |

**Team Name:Property coders**
---

**Estoria — Find your place. Make it yours.**
