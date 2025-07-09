# ListBox Component

The component includes the following features:

- Multi-selection capability.
- Search functionality to filter items.
- Conditional disabling of the component.
- Visual notifications upon submission.

---

## Features

### 1. Multi-Selection
- Items in the ListBox can be selected individually or in bulk.
- The selected state is visually indicated.

### 2. Search Functionality
- Users can search for items in the list using a search bar.
- Filters the list dynamically based on input.

### 3. Disabled State
- The ListBox and its components (items, input, button) can be disabled conditionally using the `inputDisable` property.
- Disabled state includes visual cues like a grayed-out appearance and `cursor-not-allowed` styling.

### 4. Notifications
- Displays success or error notifications after submission.
- Notifications auto-hide after 3 seconds.

![ListBox](media/default.png)
![ListBox](media/multiSelect.png)
![ListBox](media/search.png)
![ListBox](media/validation.png)
![ListBox](media/notification.png)
![ListBox](media/disable.png)