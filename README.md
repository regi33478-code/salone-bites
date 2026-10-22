# Salone Bites

**A Local Food and Restaurant Discovery Website for Sierra Leone**

Salone Bites brings Sierra Leonean dishes and restaurants together in one easy-to-use website, so people can find where to eat, what to try, and how to get there.

---

## Table of contents

- [Background](#background)
- [The problem](#the-problem)
- [The solution](#the-solution)
- [Who it is for](#who-it-is-for)
- [Pages and features](#pages-and-features)
- [Navigation](#navigation)
- [Built with](#built-with)
- [Project structure](#project-structure)
- [Getting started](#getting-started)
- [Design](#design)
- [Accessibility](#accessibility)
- [Known limitations](#known-limitations)
- [Credits](#credits)

---

## Background

Food is central to Sierra Leonean culture, identity, and social life. Dishes like Jollof Rice, Cassava Leaf, and Groundnut Stew are enjoyed daily at home, at gatherings, and in restaurants across Freetown and the rest of the country. Local restaurants such as The Mango Tree, Tasty Bites, and Krio Kitchen serve authentic dishes to a wide range of customers.

More people, especially young people and students, now search online before deciding where to eat. They expect to find menus, prices, photos, and directions quickly. Yet most Sierra Leonean restaurants still rely on word of mouth, physical signs, or scattered social media posts to reach customers.

---

## The problem

- **Scattered information:** details about local dishes and restaurants are spread across social media pages, or are not online at all.
- **Missing or outdated details:** menus, prices, opening hours, and locations are often unavailable or out of date.
- **Low visibility for small restaurants:** without a strong online presence, they lose customers to better-known places.
- **Difficulty for newcomers:** tourists, new students, and people from the diaspora do not know which dishes to try or where to find them.
- **Cultural promotion gap:** Sierra Leonean cuisine is under-promoted online compared to other cuisines.

---

## The solution

Salone Bites is a responsive, easy-to-use website that helps people discover Sierra Leonean food and restaurants in one place.

**Aim:** make local food easy to find, and promote Sierra Leonean cuisine and restaurants online.

**Objectives:**

- Give users a simple way to explore local dishes and restaurants
- Provide menus, prices, and locations in one place
- Increase the visibility of local restaurants
- Promote and preserve Sierra Leonean food culture
- Provide a clean design that works well on mobile phones

---

## Who it is for

**Primary users:** students and young professionals aged 18 to 35 who live in or around Freetown, use smartphones daily, and often decide where to eat by searching online or asking friends.

**Secondary users:** local families, tourists and visitors, Sierra Leoneans living abroad, and restaurant owners and chefs.

**What they need:**

- Easy discovery: a quick way to search for a dish, restaurant, or area
- Clear information: accurate, easy-to-read menus, prices, and descriptions
- Location help: addresses, a map, and directions
- Filtering: narrowing results by dish type, cuisine, and area
- A fast, mobile-friendly experience
- Trust: confidence that dishes and restaurants are real, local, and up to date

**Example users**

| | Mariama Kamara | Ibrahim Sesay |
|---|---|---|
| Who | 21, university student in Freetown | 34, lives abroad and visits Sierra Leone once a year |
| Wants | Affordable, tasty local food, with prices and location known before she goes | Authentic restaurants to take his family to during visits |
| Frustration | Menus and prices are rarely posted, and social media pages are cluttered | Does not know which restaurants are good or where they are |
| In her or his words | "I just want to know where to eat, what it costs, and how to get there." | "I want to take my family to real Salone food, but I don't know where to start." |

---

## Pages and features

| Page | File | What it contains |
|---|---|---|
| Home | `index.html` | Welcome banner with an "Explore food" button, popular dishes (Jollof Rice, Cassava Leaf, Groundnut Stew), and featured restaurants (Tasty Bites, Krio Kitchen, The Mango Tree) |
| About | `about.html` | The mission of promoting Sierra Leonean cuisine and supporting local farmers and chefs, and why Salone Bites exists |
| Explore | `explore.html` | The main feature: a search bar, category tabs (All, Rice, Soups, Grilled), filters by cuisine type (Traditional, Seafood, Vegetarian, Meat) and location (Freetown, Aberdeen, Lumley), and food result cards |
| Services | `services.html` | Four services (explore local food, discover restaurants, view menus and prices, find locations) and a 3-step guide: Explore, Choose, Visit |
| Contact | `contact.html` | Contact details for Freetown, a message form, and an embedded Google Map |

---

## Navigation

- **Main menu** (top of every page): Home, About, Explore, Services, Contact. The current page is highlighted.
- **Footer** (bottom of every page): About, Contact, Location.
- **Logo:** clicking "Salone Bites" returns to the Home page.
- **Call to action:** the "Explore food" button on the Home page leads to the Explore page.
- **Consistency:** the menu and footer look the same on every page, and every page is reachable within one click.

---

## Built with

- **HTML5:** semantic structure (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- **CSS3:** Flexbox and Grid layouts, one shared stylesheet (`style.css`), and media queries for tablets and phones
- No frameworks and no JavaScript libraries

---

## Project structure

```
salone-bites/
├── index.html
├── about.html
├── explore.html
├── services.html
├── contact.html
├── style.css
├── images/
│   ├── jollof.jpg
│   ├── cassava.jpg
│   └── groundnut.jpg
└── README.md
```

---

## Getting started

No installation or build step is needed.

1. Download this repository and unzip it (or click **Code → Download ZIP** on GitHub).
2. Open the `salone-bites` folder.
3. Double-click `index.html` to open the site in your web browser.

An internet connection is needed to show the hero banner, the restaurant photos, the About page photos, and the map.

---

## Design

| | |
|---|---|
| **Dark navy** (header, footer, buttons) | `#292735` |
| **Cream** (page background) | `#F7F4EC` |
| **Soft lilac** (cards and form fields) | `#d4d2e1` |
| **Sand** (active and hover links) | `#d6c7a5` |
| **Font** | Arial, Helvetica, sans-serif |

Each page is kept short and uncluttered so it is easy to scan and adapts to mobile phones.

---

## Accessibility

- Descriptive `alt` text on every image
- Labels on all form fields and on the search box
- Logical heading order on every page
- `aria-current="page"` on the active navigation link
- Visible outlines when moving through links and buttons with the keyboard
- Text colours with good contrast against their backgrounds

---

## Known limitations

- The search bar, category tabs, and filters on the Explore page show the layout only. They do not filter the results yet.
- The contact form does not send messages yet, because the site has no back end.
- Online ordering and payments are not part of this project.

---

## Credits

- Dish photos are included in the `images/` folder.
- Home hero, About page, and restaurant photos: [Unsplash](https://unsplash.com)
- Map: Google Maps embed
