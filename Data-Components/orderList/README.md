
# Order List with Item Movement

This web application allows users to manage a list of items, providing functionality for selecting, moving, and reordering the items. The items can be moved up, down, to the top, or to the bottom within the list, based on user selection. The interface is built with **Alpine.js** for interactivity and **Tailwind CSS** for styling.

## Features

- **Item Selection**: Click on an item to toggle its selection. The item will be highlighted when selected.
- **Move Items**:
  - **Move Up**: Moves the selected item(s) up by one position in the list.
  - **Move Down**: Moves the selected item(s) down by one position in the list.
  - **Move to Top**: Moves the selected item(s) to the top of the list.
  - **Move to Bottom**: Moves the selected item(s) to the bottom of the list.
- **Disable Buttons**: The movement buttons are disabled when no item is selected.

## Technologies Used

- **Alpine.js**: A minimal framework for handling interactivity, such as toggling selections and managing the list.
- **Tailwind CSS**: A utility-first CSS framework used to style the components, ensuring a responsive and modern UI.
- **SVG Icons**: SVG-based icons are used for the movement buttons (up, down, top, bottom).

## How to Use

1. **Select Items**: Click on any item in the list to toggle its selection. The item will be highlighted in white when selected.
2. **Move Items**:
   - Click the "Move Up" button to move selected items up.
   - Click the "Move Down" button to move selected items down.
   - Click the "Move to Top" button to move selected items to the top.
   - Click the "Move to Bottom" button to move selected items to the bottom.
3. **Disabled Buttons**: If no items are selected, the buttons to move items will be disabled, preventing any actions.


### HTML Structure

- The main container (`<div x-data="orderList" class="container...">`) holds the entire order list and the buttons.
- The **buttons** (`moveUp`, `moveDown`, `moveToTop`, `moveToBottom`) are used to reorder the list items.
- The **list** (`<template x-for="item in listArr"`) displays the items, and each item can be selected by clicking.

### Alpine.js Data

The `orderList` Alpine.js component manages the list of items and their movement logic. The list (`listArr`) is initialized with a set of items, each with a `click` state indicating whether the item is selected.

The movement methods are:

- `moveUp()`: Moves selected items up one position.
- `moveDown()`: Moves selected items down one position.
- `moveToTop()`: Moves selected items to the top.
- `moveToBottom()`: Moves selected items to the bottom.

### Tailwind CSS Styling

Tailwind CSS is used to create a responsive, modern interface:

- Flexbox is used to arrange the buttons and list.
- The list is styled with a scrollbar, with custom colors for selected and non-selected items.
- Button styles ensure visual feedback on hover and disable state.

![orderList](media/default.png)

![orderList](media/multiSelect.png)