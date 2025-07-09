# Tree Select Dropdown Component

The **Tree Select Dropdown** is a dynamic and interactive UI component built with **Alpine.js** and styled using **Tailwind CSS**. This component provides a hierarchical tree structure for navigating, selecting, and interacting with nodes. Its features include expand/collapse functionality, search capabilities, and customizable options.

---
![Notifications Example](media/treeSelectDefault.png)
![Notifications Example](media/multiSelectTree.png)
## Features

### 1. **Expand/Collapse**
- **Expand or Collapse All**: Easily expand or collapse all nodes in the tree.
- **Specific Node Control**: Dynamically expand or collapse individual nodes.

#### Example:
![Expand/Collapse Example](media/expandCollapse.png)

### 2. **Selection Modes**
- **Single Selection**: Allows selecting only one node at a time.
- **Multiple Selection**: Enables selecting multiple nodes using checkboxes.

#### Example:
![Multiple Selection Example](media/multiCheckbox.png)

### 3. **Search Functionality**
- **Quick Node Search**: Search for nodes by name with real-time results.
- **Highlight Matches**: Matches are highlighted and the tree expands for visibility.
- **No Results Found**: Displays a friendly message when no matches are found.

#### Examples:
- Search Results:
  ![Search Results](media/searchFunctionality.png)
- No Results:
  ![No Results](media/notFound.png)

### 4. **Notifications**
- Real-time alerts for actions like selecting, unselecting, expanding, or collapsing nodes.

#### Example:
![Notifications](media/notification.png)

### 5. **Customizability**
- Toggle display options for:
  - Selection backgrounds.
  - Checkboxes for multiple selection.
  - Expand/Collapse buttons.

---

## Demo

### Example Tree Structure
```plaintext
- Documents
  - Work
    - Expenses.doc
    - Resume.doc
  - Home
    - Invoices.txt
- Events
  - Meeting
  - Product Launch
  - Report Review
- Movies
  - Al Pacino
    - Scarface
    - Serpico
  - Robert De Niro
    - Goodfellas
    - Untouchables
