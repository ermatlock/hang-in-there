# Hang In There: Paired Project

## Project Overview
This was our first paired project as part of the Turing Front-End coding program.

Our goal was to create a motivational poster generator, with the following functionality:
- Generate a random poster using existing and updatable arrays of images, titles, and quotes
- Generate a custom poster using form input fields
- Save either a random or custom poster without duplicates
- Display the selection of saved posters in the saved Posters grid section
- Delete unwanted saved Posters with a double-click

## Instructions
The website can be viewed [here](https://ermatlock.github.io/hang-in-there/).

To download the repository: https://github.com/ermatlock/hang-in-there

### Generate Random Poster
The website will generate a random poster on page load, (and also on each page refresh). If a user wants to generate a random poster, they can also click on the, "Show Another Random Poster" button.

![Generate Random Poster](https://media.giphy.com/media/pUGmV54Pjpc1uLM7a3/giphy.gif)

### Generate Custom Poster
The user can also make their own poster with custom image, title and quote. To do this, the user will:
1. Click "Make Your Own Poster".
2. Provide an image address, title, and quote into the respective input fields.
3. Click "Show my poster".

![Generate Custom Poster](https://media.giphy.com/media/Nu2Cc1pdVhUwpCo30M/giphy.gif)

__NOTE:__ In addition to generating the users custom poster, this form will also save each piece in their respective arrays. This means that future clicks of the "Show Another Random Poster" button can display the users custom choices.

### Save Poster
The user can save either a randomly generated, or custom poster by clicking the "Save This Poster" button. This will save the poster currently displayed, and allow them to see their saved selections later by clicking the "Show Saved Posters" button.

![Save Poster](https://media.giphy.com/media/Tfb2bM38yueb7vjqM7/giphy.gif)

### Delete Poster
The user can delete a saved poster they no longer want to be saved by double clicking the respective poster on the "Show Saved Posters" page.

![Delete Poster](https://media.giphy.com/media/CQpIeuVHfeipwjT8n5/giphy.gif)

## Future Features
- Ability to drag and drop saved posters to the user's preferred order.
- View large version of saved posters upon clicking.
- Form validation and error handling functionality.
- Ability to manually update poster details within main poster view by clicking on title or quote.
- Persistent storage to keep saved posters in memory even after reload.

## Technologies Used
- Javascript
- HTML
- CSS

## Contributors
- Eric Matlock - https://github.com/ermatlock
- Nathan Hodnett - https://github.com/nhodnett
- Forked from Turing School Software and Design - (Base Javascript, HTML, CSS)

## Deploy link
- https://ermatlock.github.io/hang-in-there/
