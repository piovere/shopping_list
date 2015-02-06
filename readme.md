# Shopping List

### A simple shopping list webapp to share with my roommate

##### Models:
- List
-- Array of (thing, quantity)s
- things
-- name
-- last purchased

##### Business logic/flow:
User is presented with a list of ingredients on the current shopping list, along with quantity required. User can add new items to the list, or optionally change the quantity of an existing item (Note: should there be simple +/- buttons to require more of existing items on the list?). A text box is available to type in new items, and as the user types, a (selectable) list of previously-entered items that match the text string is presented. If the item typed does not exist in the list of things, it is automatically added to the list of things.

The user is presented with a "shop!" button, which changes the +/- buttons and editable quantity field into check boxes. These check boxes change the text style of the item they are next to into "strikethrough" when they are selected. when the user presses a "done shopping" button, these items are removed from the List
