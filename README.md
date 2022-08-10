<h1 align="center">
  Rocket Coffe - Maratona Explorer 3.0
</h1>

Developed through a maratona explorer 3.0 da Rocketeaset a website where you will have the menu of an online coffee shop.


## Layout

The following layout has been made available in https://www.figma.com/file/lEhWL1qM3SQNMiNbdJ9jd2/RocketCoffee-(Community).

## Implementation Video

https://user-images.githubusercontent.com/40831841/184015778-527baffc-bf41-4701-9562-4ce2de10d373.mp4

## More Implementations

- Adjusted for the "details" box to be the main one, so when there is no description the value is correctly on the page. Here's the CSS code:
```css
li .details {
  max-width: 240px;
  flex: 1; /* aqui faz a caixa ser considerada como principal */
}
```
- Created the footer with the information of telephone, address and all rights reserved.
- Implemented like this, when hovering over the list, underline the title and price, and the description remains as is. Here's the CSS code:
```css
li:hover h3,
li:hover strong {
  text-decoration: underline;
}
```

