# Mega Nomz


## Overview
This recipe app will help me do the following:

### 1) Search through recipes I have saved by:
- ingredients
- macros, calories, nutrients
- cuisine
- type (ex: soup, stirfry)
- meal prep-ability
- other qualities (hot, cold, comfort, healthy, light)
- pictures!!
### 2) Add more recipes:
- manually, using a form sorta thing
- via a URL to one already on the web 

## Inspiration

I like to cook, but sometimes I get stuck in a rut. I'd like an easy way that I can look for meals to make that I already know are bomb af.

Very realistic real-life examples:

_Ugh, not carrots AGAIN! This is the 13th week in a row that I've gotten them in my farm box_. I could search for a recipe that haven't made in a while that has carrots.

_Mint leaves? What the eff do I do with these?!_

_Oh shoot, these tomatoes are going bad. I need to use them asap._

_Idk what I want, but I'll know it when I see it_. Good thing there are photos!

_It's so hot outside. I need something to help cool me off_.

### Similar sites:
- [SuperCooks](https://www.supercook.com/#/desktop)
- [MyFridgeFood](https://myfridgefood.com/)


## Front-end
On the front-end, I plan to use HTML, CSS, Javascript. Maybe I'll throw in some React one day.

### Features:
- searchable (Obviously this is a huge undertaking. So I think I'd just start by being able to search for a specific ingredient.)
- can add to shopping list

## Back-end
In the backend, I'll need:
- a database (idk how yet)
- a web scraper (Python?)
  - can build my own eventually
  - but will probably start with something like [this](https://github.com/hhursev/recipe-scrapers)

### Searchable things
The database will have to store a fuck ton of stuff, such as:
- name
- link and/or source
- photo
- unordered list of ingredients
- ordered instructions
- cuisine type (ex: mexican, korean, america, etc.)
- hot / cold
- nutritional facts (by using [edamam api](https://developer.edamam.com/food-database-api-demo)?)
- general type of meal (bowl, stirfry, pasta, smoothie)
- meal type (breakfast, lunch/dinner, snack, dessert)
- meal prepable (True or False probably, i.e. can I make this ahead of time and freeze it?)

## Outline

### What this project is about:

This project will be a recipe database where I can make various types of search queries to sort through the database.

#### Header:

- Hero Image w/
  - Title
  - tagline
  - "Search" button that just skips lower on page or to another page?

#### Main content:

- left menu
  - will have all the search categories separated out (radio), not drop downs
  - ingredients will be the top one
    - is a typing search box
    - once selected, the ingredient will be generated with an X next to it (to delete it)
- recipe cards
  - grid style, responsive  
  - photo
  - recipe main
  - short blurb "easy salad that's great for putting in jars for camping" or "my go-to berry smoothie bowl with loads of toppings"

