# Double R Diner

A website for the Double R Diner designed to showcase the menu and history of the Diner itself for residents, visitors and people travelling through Twin Peaks, Washington.

This is an unofficial fan concept site for the Double R Diner from *Twin Peaks.* The rationale and everything from this line onwards treats the Diner and town as real places. 

**Live Site:** [Link here when deployed on github pages](deadlink fix this)
**Repository:** [Link to GitHub Repo](deadlink fix this)

IMAGE OF SITE HERE WHEN COMPLETED

---
## Table of Contents

1. [Project Rationale](#project-rationale)
2. [User Experience (UX)](#user-experience-ux)
	1. [Strategy](#strategy)
	2. [Scope](#scope)
	3. [Structure](#structure)
	4. [Skeleton](#skeleton)
	5. [Surface](#surface)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Testing](#testing)
6. [Deployment](#deployment)
7. [Credits](#credits)
8. [Acknowledgements](#acknowledgements)

---
## Project Rationale

This site exists to provide residents, visitors or people travelling through the town of Twin Peaks, Washington, a clear understanding of what the Double R Diner has to offer. One of the biggest issues that face consumers (specifically within the hospitality industry) is that local family-owned establishments typically tend not to have their menu online; so you're not able to research or plan your meal ahead. This is particularly an issue for tourists or travellers - locals will usually have perfect knowledge of their area and the food establishments within it, but non-locals won't. The owner currently has a huge problem; locally the Diner is known for its pie and coffee, as well as being adopted as a gathering place for the townsfolk. Right now, these core differentiators are not communicated to the target audience outside of local knowledge. 

This solves multiple problems: 
1. For the non-locals or non-regular customers of the Double R Diner, it provides them with the menu ahead of time for their consideration. This allows them to self-select if this establishment is for them, rather than arriving and taking up a table only to leave moments later once they have had a chance to read the menu. 
2. For the business, it allows them to showcase their offering to the public. It allows them to put their best foot forward with both existing and potential consumers without ever having to talk to them, as well as offering the chance to explain the history of the establishment and what makes them different. Vital marketing opportunities that are often missed, and help businesses to stand out in crowded marketplaces against chain brands.
3. Opens the door to future investment in user experience. Once a website exists, it's easier to build on it with take-away "order ahead" functionality, as well as "book a table" functions or "Order by QR code"/ "Pay by QR code", again, helping them to stand out in a crowded marketplace and put themselves on a more equitable footing against well-funded chain competitors. 

---
## User Experience

### Strategy

#### Site Owner's Goals: 
- Showcase their offering to the market
- Effectively communicate what makes them different
- Compete against chain brands

#### External User's Goals: 
- See the menu and prices ahead of time
- Decide whether this establishment is the right fit for their needs/budget
- Find out where it is, and when it's open

#### User Stories

**First-time visitor**
1. As a first time visitor, I want to know what the establishment serves and how much it costs so that I can decide if this is the kind of place I want to spend my money. 
2. As a first time visitor, I want to find out whether this establishment is open so that I don't make a wasted journey. 
3. As a first time visitor, I want to find out where this business is located so that I can plan my route ahead of time. 

**Returning visitor**
4. As a returning visitor, I want to check if the opening hours have changed so that I am not disappointed if I arrive and they are closed. 
5. As a returning visitor, I want the ability to see if the diner has regular specials so that I can try them before leaving. 
6. As a returning visitor, I want to see if there is anything specific on the menu so that I can decide if I would rather eat elsewhere if it's not. 

**Frequent visitor**
7. As a frequent visitor, I want to learn about the people behind the diner so that I can satisfy my curiosity about a local business. 
8. As a frequent visitor, I want to make sure that the Diner can accommodate a group so that I can plan a meeting with friends or family. 

### Scope

#### Features Included

| Feature                                            | User Story | Rationale                                                                                                                                                                         |
| -------------------------------------------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Main navigation                                    | all        | This serves to ensure that the user is able to quickly and easily access the page with the information they need.                                                                 |
| Hero section with diner name, tagline and location | 1, 3       | This serves to confirm the name, location and branding of the Diner itself.                                                                                                       |
| Menu page, sectioned with prices                   | 1, 6       | This serves to display the menu items on offer, allowing potential customers to either decide their order ahead of time or self-select out.                                       |
| Specials section on the menu page                  | 5          | This allows the Diner to showcase their regular daily specials.                                                                                                                   |
| Opening hours block                                | 2, 4       | This ensures that prospective customers can plan accordingly and reduces disappointment through vague opening hours.                                                              |
| Address and map image                              | 3          | This states clearly where the Diner is located, ensuring that prospective customers are able to easily find the location.                                                         |
| Directions and parking note                        | 3          | This makes it easier for non-locals to find the Diner, and alleviates any concerns about parking options.                                                                         |
| About page - history and the people                | 7          | This brings the business to life and differentiates them from an otherwise bland and faceless market crowded with chain brands.                                                   |
| Group and seating information                      | 8          | This gives locals (but others too) permission to bring larger groups and increase average spend per visit.                                                                        |
| Phone number                                       | 8          | This gives prospective customers the opportunity to easily get in touch to either book for a large group, or ask any questions that are not answered by the site.                 |
| Footer with hours, address, social links           | 2, 3, 4    | This reiterates the opening hours and locations, along with ensuring that the information is reachable from every page. It also offers alternative ways to engage with the brand. |
| 404 page                                           | -          | This exists to direct users who hit a non-existent page back to existing pages helpfully, rather than allowing them to bounce off the site.                                       |
#### Features Left to Implement

| Feature                      | Why deferred                                                                                                                                                                                                                                            |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Order ahead for takeaway     | Requires server-side order handling, a database and payment processing. Out of scope for a static HTML and CSS project.                                                                                                                                 |
| Table booking                | Requires form processing, storage of bookings and availability logic, none of which a static site is able to support.                                                                                                                                   |
| QR code ordering and payment | Dependent on the ordering system mentioned above as well as an integrated payment provider, making this perhaps the furthest from the current scope.                                                                                                    |
| Rotating dated specials      | Would require the diner to update content without editing the code, and so would require an admin interface as well as a database. The current site instead presents permanent recurring specials, which stay accurate for longer without maintenance.  |

### Structure
The site is built as four content pages plus a 404 page. Content is assigned to pages according to when a visitor is likely to need it, rather than simply by category alone. The primary audience is someone deciding whether to stop at the diner, often while travelling, so the information that decision depends on surfaces early rather than being placed behind navigation. 

#### Site Map

**Home** acts as the landing page and answers the three questions a prospective customer is likely to ask first: Is it open? Where is it? What food is the place known for? The practical details such as opening hours and location should appear above the fold alongside the Diner's name and positioning, with easy routes onward to the menu and about pages below. 

- Hero: Diner name, tagline or review, locations *(Stories 1, 3)*
- Opening hours *(Stories 2, 4)*
- Address summary and map *(Story 3)*
- Signposting to Menu and About

**Menu** showcases the full offering clearly and without assuming any local knowledge. Every item is priced and described so that a first time visitor can assess the diner on the same terms as a regular. 
- Sectioned menu with prices and descriptions *(Stories 1, 6)*
- Regular specials section *(Story 5)*

**About** differentiates the Diner from chain competitors by giving it a history and a face. This page will cover who runs it, how long it has been there, and the vital role it plays as a gathering place for the town. 
- History and the people behind the Diner *(Story 7)*
- The Diner's role within the town *(Story 8)*

**Contact** leads with the practical information a visitor is likely to require to actually arrive or get in touch. The contact form sits below this, as a secondary route rather than a primary one. The reasoning behind this is that a phone call is the fastest path for most common enquiries such as arranging a group visit, so this is given precedence. 
- Address, map, directions and parking *(Story 3)*
- Phone number and email *(Story 8)*
- Opening hours *(Stories 2, 4)*
- Contact form with HTML5 validation 

**404** page will catch visitors who accidentally reach a non-existent page and returns them to the site without requiring the use of the browsers back button. 

HOME
|_ MENU
|_ ABOUT
|_ CONACT
404 

##### Repeated Content
Opening hours and the Diner's address appear in the footer of every page as well as their dedicated sections. This is deliberate, as stories 2, 3 and 4 require this information to be available without having to hunt for it, and a visitor who lands directly on the Menu page from a search result should not have to navigate elsewhere to find out whether the Diner is open. 

##### Navigation
A single main navigation menu appears in the same position on every page, listing all four content pages. It will collapse into a toggle menu on smaller screen widths. The current page is indicated so that visitors always know where they are within the site. 

All external links (social media) will open in a new tab so that visitors are not navigated away from the site unintentionally. 

##### Information Priority
Within each page, content is ordered by inferred decision-relevance instead of narrative interest. On the Home page, this means that practical facts are before the atmosphere; on the Menu page, food precedes the framing of the establishment; on Contact, this means reaching the Diner precedes the form. Headings are used to convey this hierarchy structurally as well as visually, so the ordering is consistent and accessible for users of screen readers as well as those who are scanning the page. 

### Skeleton

#### Wireframes

Wireframes were created for all pages at three breakpoints before any code was written. 

| Page | Mobile | Tablet | Desktop|
|---|---|---|---|
| Home | link here | link here | link here |
| Menu | link here | link here | link here |
| About | link here | link here | link here |
| Contact | link here | link here | link here |

[Note for future me: I need to make sure I update this if the finished site deliberately departed from the wireframes and why.]

### Surface

#### Colour Scheme

| Colour | Hex | Used for |
|---|---|---|
