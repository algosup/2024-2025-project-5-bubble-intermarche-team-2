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
|Term | Definition|
|-----|-----------|
| Pairing technique | Also called **Cross-selling** for non-food related product. It refers to suggesting products that complement what a customer is already interested in.|
| Figma | Figma is a design and prototype tools used most commonly for web and mobile apps User Interface's. <br> Figma also allows collaboration between team members and has an animation system.|
| EAN | **E**uropean **A**rticle **N**umber is a standardized product identification number encoded in a barcode.|
| Bubble | Bubble is a tool that lets you create apps and websites without needing to know how to code. Instead of writing computer programs, you use a simple visual editor—kind of like building with digital Lego blocks.|
|Database | A database is like a table where your app stores and organizes information. <br> For example, if you're building an app that recommends products, the database would hold: <br><br> -The list of products <br> -Details about each product (name, price, image, category) <br> -Information about users (name, favorites, purchase history)|

## I. Introduction

### 1. Project Overview

This project is a mobile Application that recommends wine, cheese or both that goes with a recipe. This project has been requested by the Intermarché from Saint Rémy de Provance. 
Our contacts are Célia Moustier and Chris Cadeau. 

Chris Cadeau starts his shift early in the morning, leaving only a small lapse of time for customer to ask for recommendation before he finishes his shift in the morning.

### 2. Project Definitions

#### Project Vision

The Intermarché aims for an increase of their sells on wine and cheese by using the [**pairing technique**](#glossary) to recommend them with food recipes. The App should also be able to recommend recipes depending of which wine or cheese the client is interested in.


#### Objectives

➭ **It must be a mobile app**, ensuring offline access, geolocation and preferences registration.

➭ **The app should open swiftly** so they can access to functionalities directly instead of taking times to log in/sign up Instead of buying what they want.

➭ **The app must be user friendly** to make sure the user isn't lost in the app.

➭ **Multiple languages must be implemented** for a wider public due to the touristic flux of the region.

#### Project Scope

|In Scope|
|--------|
| Mobile App |
| Multiple Languages (At least English and French)|
| Intuitive/User friendly|

|Nice to Have|
|--------|
| Barcode Scan system (Scanning Intermarché's products)|
| Geolocation |
| The App works Offline |
| Products rating system |
| Light/Dark mode|

|Out of Scope|
|--------|
| sign in/log in system |

#### Audience

**External customers:** People coming from foreign countries for vacations and would love to buy local wine and cheese to consume french or for their cuisine.

**Local customers:** Habitants of Saint Rémy de Provance and surroundings cities/villages. They already consume frequently Intermarché products and could possibly buy other to enhance their cuisine.


#### Main deliverables

The mobile app and at least all core functionalities will be delivered to Intermarché. Mock ups will also be delivered to ensure we stay on track with Intermarché's request.

## II. Project UX and UI

### 1. Color Palette

Due to the location of the Intermarché, we decided represent France and Mediterranean sea with our color palette.

![Color Palette Image]()

*Color palette with their color code.*

We have three colors, a variant of blue, white and red. It will represents France.

The colors are slightly different compared to regular French flag, this variant also represents partially Mediterranean climate.

### 2. Font

The font we decided to use is Barlow. 

This font is simple, readable, and neutral, making it work great with the Mediterranean climate.

Barlow has rounded terminals, giving it a slightly softer, more approachable feel than other fonts. 

![Font representations]()

*different fonts including Barlow to compare.*

### 3. Image Assets

All Product images that are used for this application comes from official [Intermarché website catalog](https://www.intermarche.com/?srsltid=AfmBOorrjQq8KbjvTAbj41mkgKTv-K6JFfD5ODDhTvlTrqDv9_a71JCS).

### 4. Mockups

Mockups are produced using [**Figma**](#glossary), allowing an animated representation of the application's functionalities.

![Figma with Mockup]()

*Screenshot of the mockup on Figma.*

## III. Functional Requirement

### 1. Language selection

When the app is launched it will gives the user a language option.

![Language option page]()

*The language option page*

The user will always have the option to change the app language using the language button.

![Language button on pages]()

*Language button position on the app pages*

### 2. Product Selections

After selecting a language, the user will arrive on the main page (home menu) allowing the user to research specific products (here wine or cheese).

![Product list]()

clicking on a product will redirect the user into the specific product page, they wil get access to the different recipes that can use the product in it or pairing with it.

It also includes the product location in the Intermarché.

![Product page]()

*The product page*

### 3. Recipe List

In the same way as the products you can access the different recipes by using the same search bar, clicking on the recipe will redirect the sure on the specific recipe page.

![Recipe Page]()
*The recipe page*

### 4. Product Recommendations

Once a product or Recipe is selected, the app will recommend Intermarché products that matches along with the product.

![Schema of product recommendations system]()

*Schema of the recommendation system functionality.*
### 5. Product Scanning

Intermarché Wine can be scanned using product's [**EAN**](#glossary), directly redirecting them to the product page.

![Product scanning system representation]()

*Representation of how the scan works*

### 6. Audience

## IV. Non Functional Requirement

### 1. Geolocation

After the user select a product, the app will show the exact location of the product in the Intermarché.

### 2. Performances

#### Responsiveness

The responsiveness of an application refers to its ability to: 
- quickly respond to user interactions
- provide smooth and seamless user experiences across different devices sizes.

#### Why responsiveness is important

Responsiveness is important for the user experience, specifically the response time of the app and usability of the app.
A slow response time or a hard-to-use application will make users unsatisfied.

### 3. Technical Requirements

The App will be produced on [**Bubble**](#glossary), allowing a quick production of the app without deep coding, a responsive system, and an already made database system.

![Bubble]() ![Bubble app page]()

*Screenshots of the main page of bubble and an application starting to be produced on bubble*

For more information about the technical specificities of the project, please take a look at the [Technical Specification document]()