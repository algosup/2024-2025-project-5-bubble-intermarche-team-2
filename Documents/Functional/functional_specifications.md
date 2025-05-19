# Functional Specification

## Table of contents

- [Functional Specification](#functional-specification)
  - [Table of contents](#table-of-contents)
  - [Glossary](#glossary)
  - [I. Introduction](#i-introduction)
    - [1. Project Overview](#1-project-overview)
    - [2. Project Definitions](#2-project-definitions)
      - [Project Vision](#project-vision)
      - [Objectives](#objectives)
      - [Project Scope](#project-scope)
      - [Audience](#audience)
      - [Main deliverables](#main-deliverables)
  - [II. Project UX and UI](#ii-project-ux-and-ui)
    - [1. Color Palette](#1-color-palette)
    - [2. Font](#2-font)
    - [3. Image Assets](#3-image-assets)
    - [4. Mockups](#4-mockups)
  - [III. Functional Requirement](#iii-functional-requirement)
    - [1. Language selection](#1-language-selection)
    - [2. Product Selections](#2-product-selections)
    - [3. Recipe List](#3-recipe-list)
    - [4. Product Recommendations](#4-product-recommendations)
    - [5. Product Scanning](#5-product-scanning)
    - [6. Audience](#6-audience)
  - [IV. Non Functional Requirement](#iv-non-functional-requirement)
    - [1. Geolocation](#1-geolocation)
    - [2. Performances](#2-performances)
      - [Responsiveness](#responsiveness)
      - [Why responsiveness is important](#why-responsiveness-is-important)
    - [3. Technical Requirements](#3-technical-requirements)

## Glossary

| Term              | Definition|
| ----------------- | ----------|
| Pairing technique | Also called **Cross-selling** for non-food related product. It refers to suggesting products that complement what a customer is already interested in.                                                                                                                                                                                      |
| Figma             | Figma is a design and prototype tool commonly used for web and mobile app User Interfaces. <br> Figma also allows collaboration between team members and has an animation system.                                                                                                                                                           |
| EAN               | **E**uropean **A**rticle **N**umber is a standardized product identification number encoded in a barcode.                                                                                                                                                                                                                                   |
| Bubble            | Bubble is a tool that lets you create apps and websites without knowing how to code. Instead of writing computer programs, you use a simple visual editor—kind of like building with digital Lego blocks.                                                                                                                                   |
| Database          | A database is like a table where your app stores and organizes information. <br> For example, if you're building an app that recommends products, the database would hold: <br><br> -The list of products <br> -Details about each product (name, price, image, category) <br> -Information about users (name, favorites, purchase history) |

## I. Introduction

### 1. Project Overview

This project is a mobile Application that recommends wine, cheese, or both that go with a recipe. This project has been requested by the Intermarché from Saint Rémy de Provance.
Our contacts are Célia Moustier and Chris Cadeau.

Chris Cadeau starts his shift early in the morning, leaving only a small lapse of time for customers to ask for recommendations before he finishes his shift in the morning.

### 2. Project Definitions

#### Project Vision

The Intermarché aims for an increase in their sales of wine and cheese by using the [**pairing technique**](#glossary) to recommend food recipes. The App should also be able to recommend recipes depending on which wine or cheese the client is interested in.

#### Objectives

➭ **It must be a mobile app**, ensuring offline access, geolocation, and preferences registration.

➭ **The app should open swiftly** so they can access functionalities directly instead of taking time to log in/sign up Instead of buying what they want.

➭ **The app must be user-friendly** to make sure the user isn't lost in the app.

➭ **Multiple languages must be implemented** for a wider public due to the touristic flux of the region.

#### Project Scope

| In Scope                                         |
| ------------------------------------------------ |
| Mobile App                                       |
| Multiple Languages (At least English and French) |
| Intuitive/User-friendly                          |

| Nice to Have                                          |
| ----------------------------------------------------- |
| Barcode Scan system (Scanning Intermarché's products) |
| Geolocation                                           |
| The App works Offline                                 |
| Products rating system                                |
| Light/Dark mode                                       |

| Out of Scope         |
| -------------------- |
| sign in/login system |

#### Audience

**External customers:** People coming from foreign countries for vacations and would love to buy local wine and cheese to consume French or for their cuisine.

**Local customers:** Habitants of Saint Rémy de Provance and surrounding cities/villages. They already consume frequently Intermarché products and could buy others to enhance their cuisine.

#### Main deliverables

The mobile app and at least all core functionalities will be delivered to Intermarché. Mock-ups will also be delivered to ensure we stay on track with Intermarché's request.

## II. Project UX and UI

### 1. Color Palette

Due to the location of the Intermarché, we decided to represent France and the Mediterranean Sea with our color palette.

![Color Palette Image](/Documents/Functional/Images/color_palette.png)

_Color palette with their color code._

We have three colors, a variant of blue, white, and red. It will represent France.

The colors are slightly different compared to the regular French flag, this variant also represents a partially Mediterranean climate.

### 2. Font

The font we decided to use is Barlow.

This font is simple, readable, and neutral, making it work great with the Mediterranean climate.

Barlow has rounded terminals, giving it a slightly softer, more approachable feel than other fonts.

![Font representations](/Documents/Functional/Images/fonts.png)

_different fonts including Barlow to compare._

### 3. Image Assets

All Product images that are used for this application come from the official [Intermarché website catalog](https://www.intermarche.com/?srsltid=AfmBOorrjQq8KbjvTAbj41mkgKTv-K6JFfD5ODDhTvlTrqDv9_a71JCS).

### 4. Mockups

Mockups are produced using [**Figma**](#glossary), allowing an animated representation of the application's functionalities.

![Figma with Mockup](/Documents/Functional/Images/figma.png)

_Screenshot of the mockup on Figma._

## III. Functional Requirement

### 1. Language selection

When the app is launched it will give the user a language option.

![Language option page](/Documents/Functional/Images/language_page.png)

_The language option page_

The user will always have the option to change the app language using the language button.

![Language button on pages](/Documents/Functional/Images/language_button.png)

_Language button position on the app pages_

### 2. Product Selections

After selecting a language, the user will arrive on the main page (home menu) allowing the user to research specific products (here wine or cheese).

![Product list](/Documents/Functional/Images/product_list.png)

Clicking on a product will redirect the user to the specific product page, they will get access to the different recipes that can use the product in or paired with it.

It also includes the product location in the Intermarché.

![Product page](/Documents/Functional/Images/product_page.png)

_The product page_

### 3. Recipe List

In the same way as the products you can access the different recipes by using the same search bar, clicking on the recipe will redirect the sure to the specific recipe page.

![Recipe Page](/Documents/Functional/Images/recipe_page.png)
_The recipe page_

### 4. Product Recommendations

Once a product or Recipe is selected, the app will recommend Intermarché products that match along with the product.

![Schema of product recommendations system](/Documents/Functional/Images/recommendation_workflow.png)

_Schema of the recommendation system functionality._

### 5. Product Scanning

Intermarché Wine can be scanned using the product's [**EAN**](#glossary), directly redirecting them to the product page.

![Product scanning system representation](/Documents/Functional/Images/product_scanning.png)

_Representation of how the scan works_

### 6. Audience

![Use case1](/Documents/Functional/Images/use_case_1.png)

![Use case2](/Documents/Functional/Images/use_case_2.png)

## IV. Non Functional Requirement

### 1. Geolocation

After the user selects a product, the app will show the exact location of the product in the Intermarché.

### 2. Performances

#### Responsiveness

The responsiveness of an application refers to its ability to:

- quickly respond to user interactions
- provide smooth and seamless user experiences across different device sizes.

#### Why responsiveness is important

Responsiveness is important for the user experience, specifically the response time of the app and the usability of the app.
A slow response time or a hard-to-use application will make users unsatisfied.

### 3. Technical Requirements

The App will be produced on [**Bubble**](#glossary), allowing a quick production of the app without deep coding, a responsive system, and an already-made database system.

![Bubble](/Documents/Functional/Images/bubble.png) ![Bubble app page](/Documents/Functional/Images/bubble_app_page.png)

_Screenshots of the main page of Bubble and an application starting to be produced on Bubble_

For more information about the technical specificities of the project, please take a look at the [Technical Specification document](/Documents/Technical/technical_specification.md)
