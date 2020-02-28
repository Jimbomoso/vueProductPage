# Product page

## Link to demo:

https://jimbomoso.github.io/vueProductPage/

## About

    This is an exercise straight from Vue where you develop a product page.

## Tech

- HTML
- CSS
- Javascript
- Vue.js

### Notes

- Clicking on shipping or details shows associated content
- Each color is a different product number. Hovering over a color displays that product number's content.
- Each product has an inventory level. If a product's inventory is 0 it will display out of stock and the add to cart button is disabled. If a product's inventory is > 0 it will show in stock and the add to cart button will be enabled.
- Clicking add to cart will add that specific item number to cart array. This means if you add two green socks and one blue sock the cart array will reflect that data. By default the blue socks are set to 0 inventory to show the preceeding feature. This can be seen by installing Chrome's dev tools vue extension and going to the view tab in dev tools after.
- Clicking on reviews will show reviews for the item. If there aren't any reviews, which is the default, this will be displayed.
- Clicking on make a review will display a review form.
- Partially completing a review form will not allow submitall.
- After completing a review you can click on the reivews tab and see the reviews. Refreshing the page erases the reviews as they are only stored in sessions storage in this exercise.
