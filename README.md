# Simple Color List
A simple CRUD app containing a list of colors in hex color code, #fff = white. I visit this list when I'm searching for a color to use on my other projects. Users can add on to the list by commenting in the textarea and hitting the submit button. The page will reload and the new color will appear on the bottom of the list. Users can change the background of the page by clicking an item(color) on the list, handy since all colors are in hex code.

**Link to project:** https://simple-color-list.herokuapp.com/

![Color List](https://i.ibb.co/BKzvTgX/colorlist01.png)
![Color List](https://i.ibb.co/8NjpvRV/colorlist02.png)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, EJS, node.js, Express, MongoDB

The background color change is made with client side javascript. CRUD is handled on the server.js file. I used CSS to center the list and the border around it. EJS handles the new color appearing on the list with a for(loop). There was a delete button next to each color but I commented it out so no-one deletes it. I didnt intend this to be shared with the public but I open it now if anyone wants to use these colors or add their own to the list!

## Optimizations

If I were to do this all over again, I would add a signup feature so they can have their own personal color list.

## Lessons Learned:

Taught me about CRUD and how to deploy on heroku

## Examples:
Take a look at these few examples that I have in my own portfolio:

**Dora | socail Q & A web app:** https://github.com/leandro-alba/dora3

**MVC lecture:** https://github.com/leandro-alba/todo-mvc

**Happy Notes:** https://github.com/leandro-alba/happy-notes
