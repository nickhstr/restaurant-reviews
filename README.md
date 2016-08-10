# Restaurant Reviews

A site for restuarant reviews, designed from the ground-up for accessibility. [Check it out!](https://nickhstr-restaurant-reviews.firebaseapp.com)

## Accessible

With accessibility in mind from the get go, this app is user-friendly for every user. No matter if they're blind, physically limited, color-blind, or just don't have both hands free, this app proves to be easy to use for all users.

## Using the App

Feel free to navigate with or without the mouse, or even without looking at the screen! This app is intentionally simple, consiting of only a few main views: home, restaurants, and reviews; the home view serves as a landing page, the restaurants view holds all the restaurants (with sorting/filtering of the restaurants available), and each restaurant has a link to its reviews page, holding all reviews and the option to write your own.

## Build Process

Good ol' polymer-cli is here to save the day! In order to build and serve the app locally:

- Clone the repo and `cd` into the `restaurant` directory
- Make sure to have bower and polymer-cli installed `npm install -g polymer-cli bower`
- Run `bower install`
- Run `polymer build`
- After the build completes, cd into either `build/bundled` or `build/unbundled`
- And finally, serve the app with `polymer serve`