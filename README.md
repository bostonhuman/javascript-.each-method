# JavaScript .each() method

This example creates a jQuery object containing all of the list items from the page. The .each() method is then used to loop through the list items and run an anonymous function for each of them. The anonymous function takes the value from the id attribute on the li element and adds it to the text in the list item.

# Components that make the app run

* The selector creates a jQuery object containing all li elelemts. The .each() method calls an anonymous function for each of the list items in the matched set.
* The this keyword refers to the current element node in the loop. It is used to access the value of the current element's id attribute, which is stored in a variable called ids.
* $(this) is used to create a jQuery object that contains the current element in the loop. Having the element in a jQuery object enables you to use jQuery methods on that element. In this case the .append() method is used to add a new span element to the current list item.

## How to run the app?
* In your terminal:
```
git clone https://github.com/bostonhuman/javascript-.each-method
```
* Open `each.html` to run the app.
