# NatashaElistratova.github.io
This project is inspired by AadumKhor Go check out his flutter implementation of the same Here .

How to play

Drag and Drop [Chrome,Opera]:-

Drag the card or the card pile you want to move.
Drop the dragged card pile on the target and if the move is legal card will move
Note:- Drag and Drop doesn't work for properly for firefox due to their lack of support to html Drag and drop API - https://bugzilla.mozilla.org/show_bug.cgi?id=505521 .
Click edition [Mobile,Firefox,Chrome,Safari,Opera]-

Click on the card or card pile you want to move .The pile turns to blue.
Click on the destination card and if the move is legal the cards will stack below the target.
About the project.

Drag and Drop

Drag and drop is implemented with native html5 drag and drop api with @drag, @dragend, @dragenter eventlisteners on the Card.vue component.
Libraries like Vue.draggable were not used as i had to write most of the drag and drop logic according to the solitaire game type and I also had to MOVE the stack of cards.
Ghost image in drag is removed instead the whole stack of card moves with cursor change.
CSS

Each and every card is 100% css except the SVG of the suit in the center of the card,which is made by illustrator tool.
