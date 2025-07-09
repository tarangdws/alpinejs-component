# MultiSelect Dropdown Component

The MultiSelect Dropdown component includes the following features:

- Multi-selection capability with chip display.
- Search functionality to filter cities.
- Conditional disabling of the dropdown and its interactions.
- Notifications upon form submission.
- "Select All" and "Remove All" options.

---

## Features

### 1. Multi-Selection
- Users can select multiple items from the dropdown.
- Selected items are displayed as chips (or a summary text if more than 3 are selected).
- Chips allow users to remove individual items by clicking the close button.

### 2. Search Functionality
- A built-in search bar allows users to filter items in real time.
- The list dynamically updates based on the search query.

### 3. Disabled State
- The dropdown and its input can be disabled conditionally using the `inputDisable` property.
- Disabled state provides visual feedback, including grayed-out input and `cursor-not-allowed` styling.

### 4. Notifications
- Displays notifications upon form submission or interactions.
- Notifications auto-hide after 3 seconds or can be manually dismissed.

### 5. "Select All" and "Remove All" Options
- A "Select All" checkbox allows users to quickly select all items in the list.
- The "Remove All" button clears all selected items.

---

![MultiSelect](media/default.png)
![MultiSelect](media/errMsg.png)
![MultiSelect](media/chips.png)
![MultiSelect](media/allselect.png)
![MultiSelect](media/checkedDisplay.png)
![MultiSelect](media/removeBtn.png)
![MultiSelect](media/notification.png)