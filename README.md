It is not easy switching from vanilla css to tailwind.
Took a while to understand setting of margin.
At first i used the background in the body but realized it wont achieve the goal as the image is not stretched to the height of the page hence had to use another approach of creating another div and using absolute and relative including using z-index to place the text in front of the background.
Another issues i had was sizing the buttons. Had to use w-[] and converted the px to rem to achieve the responsiveness needed.
