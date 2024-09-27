# User Management Screen UI Specification

## UI Components

### 1. User List Table
- Displays a list of existing users
- Columns:
  - ID (sortable)
  - User Name (sortable)
  - Email (sortable)
  - Enabled status (sortable)

### 2. New User Button
- Label: "+ New User"
- Position: Top left of the screen
- Action: Opens the New User form

### 3. Hide Disabled User Toggle
- Label: "Hide Disabled User"
- Position: Top right of the screen
- Action: Filters out disabled users from the list when toggled

### 4. New User Form
- Fields:
  - Username (text input)
  - Display Name (text input)
  - Phone (text input)
  - Email (text input)
  - User Roles (dropdown
      - options : Guest , Admin ,SuperAdmin
  - Enabled (checkbox)
- Save User button at the bottom

## Behavior

### Page Load
- Display the user list table with existing users
- New User form should be hidden initially

### Adding a New User
1. Click "+ New User" button
2. New User form appears on the right side
3. Fill in user details
4. Select user role(s) from the dropdown
5. Check/uncheck the Enabled box
6. Click "Save User" to add the user to the list

### Sorting
- Clicking on column headers in the user list table should sort the list based on that column

### Filtering
- Toggling "Hide Disabled User" should update the list , and now shown hided users.
