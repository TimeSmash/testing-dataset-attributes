# testing-dataset-attributes
Small examples of how to use HTML5 data attributes. Related to the Medium article "Using Dataset Attributes in HTML5". 
Link: PUT LINK HERE

## Example 1: Using Data Attributes to Selectively Alter Element Visibility

In this example, we have three recipe cards. Each card is a div, and each div has a data-diet attribute. Clicking the "Show Only Vegetarian" button enables a JavaScript function that assesses the data-diet attributes of each recipe card. If the data-diet is not vegetarian, the card becomes invisible via CSS manipulation.

## Example 2: Using Data Attributes And Keycodes to Alter text in an element

In this example, we have divs that contain letters, and each div has a data-key attribute. By setting event listeners to listen for the letters inside each div as a keyboard press, we can then derive those letter's keycodes. The data-key attribute is each letter's corresponding keycode--by comparing it and the key that was pressed, we can selectively alter the text within certain divs. 
